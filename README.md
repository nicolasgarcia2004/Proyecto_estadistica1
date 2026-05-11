# Proyecto Final - Estadística 1: Análisis de Accidentes de Tráfico

## Descripción

Este repositorio contiene el proyecto final de la asignatura **Estadística 1** de la Universidad Industrial de Santander (UIS). El trabajo consiste en un Análisis Exploratorio de Datos (EDA) sobre el dataset público [Traffic Accidents](https://www.kaggle.com/datasets/oktayrdeki/traffic-accidents/data) disponible en Kaggle.

El objetivo del proyecto es aplicar los conceptos estadísticos vistos en clase para analizar datos reales de accidentes de tráfico, identificando patrones, factores de riesgo y tendencias que puedan ser útiles para la toma de decisiones en seguridad vial.

## Dataset

El dataset utilizado fue obtenido de Kaggle y contiene registros de accidentes de tráfico con múltiples variables tanto cualitativas como cuantitativas.

### Variables seleccionadas para el análisis

**Cualitativas:**
- Dispositivo de control de tráfico (semáforo, señal de pare, sin controles, etc.)
- Condición climática (despejado, lluvia, nieve, etc.)
- Condición de iluminación (luz del día, oscuridad, anochecer, etc.)
- Día de la semana del accidente
- Gravedad de las lesiones (sin lesión, no incapacitante, incapacitante, mortal)

**Cuantitativas:**
- Número de vehículos involucrados
- Total de lesiones
- Lesiones fatales
- Hora del accidente
- Mes del accidente

## Contenido del notebook

El notebook `Proyectoestadistica1.ipynb` incluye las siguientes secciones:

1. **Carga y limpieza de datos** - Lectura del dataset, selección de variables relevantes, traducción de categorías al español y tratamiento de valores faltantes.

2. **Análisis univariado de variables cuantitativas** - Histogramas de frecuencia absoluta y relativa para las variables numéricas, incluyendo visualizaciones en escala logarítmica para observar mejor la distribución de los datos.

3. **Análisis univariado de variables cualitativas** - Diagramas de barras y tablas de frecuencia para cada variable categórica del estudio.

4. **Análisis bivariado** - Boxplots, strip plots y gráficos de dispersión (scatter plots) para explorar la relación entre variables como el número de vehículos involucrados, el total de heridos y la gravedad de las lesiones.

Cada sección incluye su respectivo análisis e interpretación de los resultados obtenidos.

## Herramientas utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab (entorno de desarrollo)

## Cómo ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/nicolasgarcia2004/Proyecto_estadistica1_analisis_accidentes.git
   ```
2. Abrir el archivo `Proyectoestadistica1.ipynb` en Google Colab o Jupyter Notebook.
3. Ejecutar las celdas en orden.

El dataset se carga desde una URL remota, por lo que se necesita conexión a internet.

## Algunos resultados

- La gran mayoría de accidentes registrados involucran 2 vehículos.
- Se encontraron patrones temporales relevantes en cuanto a la hora y el mes de ocurrencia de los accidentes.
- Las condiciones despejadas son las más frecuentes al momento de los accidentes.
- Existe una relación observable entre el número de vehículos involucrados y la cantidad de heridos, diferenciada según la gravedad de las lesiones.

---

Proyecto desarrollado como parte de la asignatura de Estadística 1, Universidad Industrial de Santander.
