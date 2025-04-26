# dashboard_ventas_demo
Es un Dashboard básico de Ventas utilizado para dar capacitaciones y demos, pero que puede ser usado por cualquier persona/comercio para aprender sobre la herramienta Power BI y analizar sus datos.

## Instalación
1. Descargar e instalar Power BI Desktop. [Link descarga](https://www.microsoft.com/es-es/power-platform/products/power-bi/downloads)
2. Descargar el archivo plantilla y el Excel con los datos: dashboard_ventas_datos.xlsx y dashboard_ventas.pbit. [Link descarga](https://github.com/gerardo-boiero/dashboard_ventas_demo/archive/refs/heads/master.zip) 
3. Completar el archivo de datos dashboard_ventas_datos.xlsx con sus propios datos. Importante: No se puede eliminar hojas ni cambiar de nombres a las columnas.
4. Abrir el archivo de plantilla de PowerBI en Power BI, y le solicitará que complete la ubicación y nombre del archivo de datos para conectarlo a sus propios datos. El parámetro a completar debe ser similar a:  C:\Ejemplo PBI\demo_ventas\dashboard_ventas_datos.xlsx
5. Luego, se actualizará el Dashboard de PowerBI con sus datos. Cada vez que se realicen modificaciones en el archivo Excel, deberá Actualizar los datos en Power BI.
   
##Descripción
El dashboard cuenta con __5 páginas dinámicas__ y __filtros por año y mes__, para facilitar la exploración y el análisis de la información:

*Visión general de las ventas
*Ventas por clientes
*Ventas por productos
*Ventas por sucursales/vendedores
*Comparación de ventas por año

El modelo de datos cuenta con __5 dimensiones__ (Cliente, Sucursal, Producto, Vendedor, Calendario) y __1 tabla de hechos__ (Ventas).
