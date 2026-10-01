#  Análisis Financiero y Pipeline ETL Automatizado - Andina Comercial

##  Objetivo del Proyecto
Desarrollo de una solución analítica integral (End-to-End) para automatizar el procesamiento de datos financieros y comerciales. El proyecto transforma datos transaccionales crudos en un P&L (Estado de Pérdidas y Ganancias) dinámico, permitiendo a los directivos evaluar la rentabilidad (EBIT) y el cumplimiento de presupuestos en tiempo real.

##  Arquitectura y Tecnologías
*   **Extracción y Transformación (Python / Pandas):** Limpieza de datos `.csv`, estandarización de formatos y validación de calidad desde Google Colab.
*   **Carga y Almacenamiento (API gspread / Google Sheets):** Ingesta automatizada hacia un Data Warehouse ligero en la nube, eliminando la dependencia de archivos estáticos.
*   **Modelado (Power BI / Power Query):** Conexión web al repositorio en la nube, limpieza final y construcción de un Modelo de Datos en Estrella (Star Schema).
*   **Análisis y Visualización (DAX):** Desarrollo de un dashboard ejecutivo con métricas financieras complejas (Ventas Netas, COGS, EBIT, Variación de Presupuesto).

##  Impacto de Negocio
*   Reducción del tiempo de reporte manual a 0 mediante la conexión directa a la nube.
*   Identificación clara de los márgenes de rentabilidad por categoría de producto y segmento de cliente.
*   Monitorización de la ejecución del gasto operativo frente al presupuesto asignado.
https://docs.google.com/spreadsheets/d/17cxzC82uXKlmg0fU4OkdFRevFSBIgtHD-07uHX8BisQ/edit?usp=sharing
