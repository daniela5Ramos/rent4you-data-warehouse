# Rent4you Data Warehouse

Este repositorio contiene los datos y scripts utilizados para el diseño del data warehouse de la compañía de alquiler de vehículos Rent4you.

## Estructura del Proyecto

- `data/`: Contiene los datos generados en formato CSV.
  - `dim_tiempo.csv`
  - `dim_cliente.csv`
  - `dim_sucursal.csv`
  - `dim_vehículo.csv`
  - `dim_empleado.csv`
  - `fact_ventas.csv`

- `notebooks/`: Contiene los Jupyter Notebooks con la generación y preprocesamiento de datos.
  - `generate_data.ipynb`: Notebook para generar los datos.
  - `preprocess_data.ipynb`: Notebook para preprocesar los datos de ventas por sucursal.

- `outputs/`: Contiene los datos preprocesados listos para el análisis.
  - `ventas_sucursal_preprocesado.csv`: Archivo CSV con el análisis de ventas por sucursal.

## Instrucciones

1. **Generar los Datos**:
   - Abra el notebook `generate_data.ipynb` y ejecute todas las celdas para generar los archivos CSV en la carpeta `data/`.

2. **Preprocesar los Datos**:
   - Abra el notebook `preprocess_data.ipynb` y ejecute todas las celdas para generar el archivo preprocesado `ventas_sucursal_preprocesado.csv` en la carpeta `outputs/`.


