#  Análisis de Ventas – Proyecto de Portafolio

##  Archivo Analizado
`ventas_2024.xlsx`

## 🧾 Descripción del Proyecto
Este proyecto consiste en el análisis exploratorio de un archivo de ventas. Se realiza limpieza de datos, cálculos de métricas clave y visualización de tendencias para evaluar el comportamiento de las ventas a lo largo del tiempo.

##  Columnas del Dataset
- `Mes`: Periodo de la venta (ej. Enero, Febrero, etc.)
- `Ventas`: Monto total de ventas en ese mes

## Herramientas Utilizadas
- **Python (Jupyter Notebook)
- **pandas** para análisis de datos
- **matplotlib** para visualizaciones

##  Análisis Realizado
- Carga y visualización del archivo Excel
- Agrupación de datos por mes
- Cálculo del porcentaje de crecimiento mensual (`pct_change`)
- Redondeo de métricas a 2 decimales
- Visualización con gráfico de barras de las ventas por mes

## Aprendizajes Clave
- Uso de `.groupby()` y funciones estadísticas como `.sum()` y `.pct_change()`
- Manipulación de columnas y creación de nuevas variables
- Generación de visualizaciones limpias y personalizadas
- Diferencia entre acceso a columnas con `df['col']` y `df.col`

## 📌 Resultado
Gráfico de crecimiento de ventas mes a mes, y tabla limpia con porcentajes redondeados.
