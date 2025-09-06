# Zuber Taxis - Análisis de datos

## Descripción
Zuber es una nueva empresa de viajes compartidos que se está lanzando en Chicago. Este repositorio fue creado como ejercicio para practicar análisis de datos. A partir de una base de datos con información de competidores y del clima, se busca probar la hipótesis de que las condiciones meteorológicas influyen en la frecuencia de los viajes. Mi tarea principal es encontrar patrones en la información disponible.

## Objetivo
Comprender las preferencias de los pasajeros y la relación que hay entre ellas y el impacto de los factores externos en los viajes. Los hallazgos permitirán identificar qué condiciones favorecen la demanda y cómo Zuber puede utilizar esta información al planificar su entrada al mercado de Chicago.

## Herramientas utilizadas
- **Python** 3.x
- **Jupyter Notebook** para el desarrollo interactivo
- **Pandas** y **NumPy** para la manipulación y el análisis de datos
- **Matplotlib** y **Seaborn** para la visualización
- **SciPy** para pruebas estadísticas
- **Requests** para obtener datos externos
- Consultas **SQL** cuyos resultados están exportados en archivos CSV

## Estructura del repositorio
- `zuber_chicago_taxis.ipynb`: cuaderno principal con el análisis.
- `moved_project_sql_result_01.csv`, `moved_project_sql_result_04.csv` y `moved_project_sql_result_07.csv`: resultados de consultas SQL sobre los datos de viajes.
- `duplicated_rows_trips_loop_ohare.csv`: datos auxiliares para la zona entre Loop y O'Hare.

## Uso
1. Clonar este repositorio.
2. Abrir `zuber_chicago_taxis.ipynb` con Jupyter Notebook o Jupyter Lab.
3. Ejecutar las celdas en orden para reproducir los análisis y visualizaciones.

## Próximos pasos
- Incorporar datos históricos del clima para profundizar en la hipótesis.
- Desarrollar modelos predictivos que relacionen el clima y la demanda de viajes.
