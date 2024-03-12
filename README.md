# Proyecto de Segmentación de Clientes

## Descripción
Este proyecto aplica técnicas avanzadas de clustering para segmentar la base de datos de clientes de un centro comercial. El objetivo es identificar patrones distintos en el comportamiento y las características de los clientes, permitiendo desarrollar estrategias de marketing más dirigidas y personalizadas.

## Metodología
El análisis se llevó a cabo en varias etapas clave:

1. **Importación de librerías y datos**: Se utilizaron librerías estándar de ciencia de datos para cargar y examinar el conjunto de datos.
2. **Análisis Exploratorio de Datos (EDA)**: Se realizó un EDA para entender la distribución y las características de los datos, incluyendo la búsqueda de valores nulos y la exploración de la distribución de características importantes como género, edad e ingresos.
3. **Preprocesamiento de Datos**: Se codificaron variables categóricas y se normalizaron las características numéricas. Además, se crearon nuevas columnas categóricas para representar agrupaciones lógicas en edad, ingresos y nivel de gasto.
4. **Clustering**:
   - Aplicamos K-Means y Clustering Jerárquico para segmentar a los clientes basándonos en características seleccionadas.
   - Se utilizó el método del codo y el análisis de silueta para determinar el número óptimo de clusters.

## Datos
El conjunto de datos contiene las siguientes variables para cada cliente:
- `CustomerID`: Identificador único.
- `Gender`: Género.
- `Age`: Edad.
- `Annual Income (k$)`: Ingresos anuales.
- `Spending Score (1-100)`: Índice de gastos basado en el comportamiento de compra y la utilización de servicios en el centro comercial.

## Resultados
La segmentación reveló patrones distintivos entre los clientes, diferenciándolos por género, edad, ingresos y hábitos de gasto. Los clusters identificados proporcionan insights valiosos para el desarrollo de estrategias de marketing dirigidas:

### Clusters para Mujeres
- **Cluster 0**: Altos ingresos y alto nivel de gastos, principalmente de edad adulta.
- **Cluster 1**: Ingresos bajos y gasto variado, más jóvenes.
- **Cluster 2**: Ingresos bajos, con equilibrio en gasto bajo, medio y alto.

### Clusters para Hombres
- **Cluster 0**: Ingresos bajos y gasto principalmente bajo.
- **Cluster 1**: Edad madura, equilibrio entre ingresos bajos y medios, y gasto predominante medio.
- **Cluster 2**: Altos ingresos, distribución equilibrada de niveles de gasto.
- **Cluster 3**: Jóvenes con ingresos bajos, divididos entre gasto bajo y alto.

## Conclusiones
Este análisis de segmentación destaca la importancia de personalizar las estrategias de marketing para diferentes segmentos de clientes. Los insights obtenidos pueden guiar la creación de campañas dirigidas que resonarán mejor con los intereses y necesidades específicos de cada grupo.

## Instalación y Configuración
Para ejecutar este proyecto, necesitarás instalar Python y algunas librerías de Python. Aquí te mostramos cómo configurar tu entorno:

1. Instala Python 3 si aún no lo tienes.
2. Clona este repositorio a tu máquina local.
3. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt


## Uso
Para utilizar este proyecto y llevar a cabo el análisis de segmentación de clientes, sigue los siguientes pasos:

1. Abre el notebook denominado `customer_segmentation.ipynb` utilizando Jupyter Notebook o JupyterLab.
2. Procede a ejecutar todas las celdas del notebook, las cuales están diseñadas para realizar el análisis paso a paso. Puedes hacerlo seleccionando cada celda y pulsando `Shift + Enter`, o utilizando la opción de ejecutar todas las celdas en el menú del Jupyter.
3. Una vez completado el análisis, revisa los resultados y las visualizaciones generadas para obtener una comprensión clara de los distintos segmentos de clientes identificados.

Estas instrucciones te ayudarán a navegar y entender el proceso de segmentación de clientes llevado a cabo en este proyecto.

