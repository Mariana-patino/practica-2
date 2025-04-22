# practica-2

#  Sistema de Gestión de Ventas de Vehículos en Prolog

##  Descripción
Este proyecto fue desarrollado para la asignatura **ST0244 - Lenguajes de Programación**. Consiste en un sistema de gestión de inventario de vehículos utilizando **Prolog**, que permite realizar consultas filtrando por tipo, marca, presupuesto, entre otros criterios.

##  Predicados principales

- `vehicle/5`: Representa los vehículos en el inventario.
  - Estructura: `vehicle(Marca, Referencia, Tipo, Precio, Año).`
- `meet_budget/2`: Filtra vehículos por referencia y presupuesto máximo.
- `generate_report/4`: Genera un reporte con una lista filtrada de vehículos por marca, tipo y presupuesto, e incluye el valor total.
- Uso de `findall/3` y `bagof/3` para agrupar y recolectar datos.

##  Casos de prueba implementados

1. **Listar referencias Toyota tipo SUV** con precio inferior a $30,000.
2. **Mostrar vehículos de la marca Ford**, agrupados por tipo y año, utilizando `bagof/3`.
3. **Calcular el valor total** del inventario filtrado por tipo *Sedán*, sin exceder $500,000.

## ▶ Cómo ejecutar el programa

1. Abrir el archivo `.pl` en **SWI-Prolog** o alguna herramienta en línea como **JsCoq**.
2. Cargar el archivo y probar los predicados directamente desde la consola.
3. Usar los casos de prueba como ejemplos de consulta.

## 📂 Archivos entregados

- Código fuente en Prolog (.pl)
- Capturas de pantalla o ejemplos de ejecución
- Video explicativo
- Este `README.md`

## 👥 Integrantes del grupo

- Mariana Patiño
- Maria Jose Holguín
