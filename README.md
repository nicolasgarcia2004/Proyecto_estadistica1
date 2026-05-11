# 📊 Análisis Estadístico de Accidentes de Tráfico 🚑🚦

## 🌍 Introducción

Los accidentes de tráfico representan una grave preocupación global en materia de salud pública, siendo una de las principales causas de mortalidad y lesiones severas que afectan a millones de personas anualmente. Ante esta problemática apremiante, el presente trabajo se embarca en un **Análisis Exploratorio de Datos** detallado del conjunto de datos "Traffic Accidents".

Nuestro objetivo es ir más allá de las cifras superficiales, buscando identificar patrones significativos, descubrir factores de riesgo latentes y discernir tendencias clave que influyen en la ocurrencia y la gravedad de estos siniestros viales. Mediante una exploración visual y estadística exhaustiva de este dataset, aspiramos a transformar los datos brutos en información valiosa y actionable que impulse la toma de decisiones informadas, y que, en última instancia, contribuya directamente a la mejora sustancial de la seguridad vial en nuestras comunidades.

## 📌 Importancia del estudio

Este análisis proporciona información valiosa para:
- 🏛️ Diseño de políticas públicas efectivas  
- 🛡️ Implementación de medidas preventivas  
- 💔 Reducción de mortalidad vial  
- 🚨 Optimización de recursos de emergencia  

## 📚 Fuente de Datos

Los datos utilizados en este análisis fueron obtenidos del dataset público:  
🔗 [Traffic Accidents Dataset](https://www.kaggle.com/datasets/oktayrdeki/traffic-accidents/data) en [Kaggle](https://www.kaggle.com)

## 📋 Variables del Estudio

### 🔠 Variables Cualitativas

| Variable | Descripción | Ejemplo de valores |
|----------|-------------|--------------------|
| 🚦 `DispositivoControlTrafico` | Control de tráfico presente | Semáforo, señal stop |
| 🌧️ `CondicionClimatica` | Clima durante el accidente | Lluvia, soleado |
| 💡 `CondicionIluminacion` | Condiciones de luz | Día, noche con luces |
| 📅 `DiaSemanaAccidente` | Día de ocurrencia | Lunes, Domingo |
| 🏥 `GravedadLesiones` | Severidad del accidente | Fatal, leve |

### 🔢 Variables Cuantitativas

| Variable | Descripción | Rango típico |
|----------|-------------|-------------|
| 🚗 `NumeroVehiculos` | Nº de vehículos involucrados | 1-10 |
| 🤕 `LesionesTotales` | Personas lesionadas | 0-50 |
| ⚰️ `LesionesFatales` | Lesiones mortales | 0-10 |
| ⏰ `HoraAccidente` | Hora del accidente (24h) | 0-23 |
| 🗓️ `MesAccidente` | Mes de ocurrencia | 1-12 |

## 🎯 Objetivo Principal

Identificar patrones, factores de riesgo y tendencias en accidentes de tráfico para mejorar la seguridad vial.

## 🔬 Metodología y Análisis Realizados

El análisis fue desarrollado en Python utilizando un Jupyter Notebook (`Proyectoestadistica1.ipynb`), aplicando las siguientes técnicas estadísticas y de visualización:

### 1. Carga y Preparación de Datos
- Lectura del dataset desde fuente remota (Google Drive)
- Selección de columnas representativas para el análisis
- Traducción de las variables al español para mejor comprensión
- Limpieza de datos: eliminación de valores vacíos y NaN
- Renombrado de columnas con nomenclatura descriptiva

### 2. Análisis de Distribución de Variables Cuantitativas
- **Histogramas de frecuencia absoluta y relativa**: Para visualizar la distribución del número de vehículos por accidente
- **Histogramas en escala logarítmica**: Para identificar patrones en datos con distribución sesgada
- **Análisis de frecuencias de hora y mes del accidente**: Identificación de patrones temporales

### 3. Análisis de Variables Cualitativas
- **Diagramas de barras**: Para dispositivo de control de tráfico, condición climática, condición de iluminación, día de la semana y gravedad de lesiones
- **Tablas de frecuencia**: Frecuencias absolutas y relativas de cada categoría

### 4. Análisis Bivariado
- **Boxplots (Diagramas de caja)**: Distribución de lesiones totales según gravedad
- **Strip plots**: Distribución detallada de heridos totales según gravedad de lesiones
- **Scatter plots (Gráficos de dispersión)**: Relación entre número de vehículos y heridos totales, coloreados por gravedad de lesiones

### 5. Herramientas Utilizadas
- **Python** como lenguaje de programación
- **Pandas** para manipulación y análisis de datos
- **NumPy** para operaciones numéricas
- **Matplotlib** para visualización de datos
- **Seaborn** para visualizaciones estadísticas avanzadas
- **Google Colab** como entorno de desarrollo

## 📈 Hallazgos Principales

1. **Distribución de vehículos**: La mayoría de los accidentes involucran 2 vehículos, con una disminución exponencial para números mayores.

2. **Patrones temporales**: Se identificaron horas y meses del año con mayor incidencia de accidentes.

3. **Condiciones climáticas**: Las condiciones despejadas son las más frecuentes en los accidentes registrados.

4. **Gravedad de lesiones**: La categoría "Sin indicio de lesión" muestra consistentemente cero heridos, mientras que las categorías de lesión no incapacitante e incapacitante presentan la mayor concentración de incidentes con heridos.

5. **Relación vehículos-lesiones**: Se observó una correlación entre el número de vehículos involucrados y la cantidad de heridos totales, con patrones diferenciados según la gravedad de las lesiones.

## 👥 Autores

Este análisis fue realizado por:

| Nombre | Código |
|--------|--------|
| Harver Alejandro Sierra García | 2204124 |
| Javier Alejandro Silva Murillo | 2211860 |
| Nicolas Esteban Garcia Tamayo | 2211233 |

## 🏫 Institución

**Universidad Industrial de Santander**  
Proyecto Final - Asignatura de Estadística 1

## 📝 Cómo Ejecutar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/Proyecto_estadistica1.git
   ```

2. Abre el notebook `Proyectoestadistica1.ipynb` en Google Colab o Jupyter Notebook.

3. Ejecuta todas las celdas secuencialmente.

> **Nota**: El dataset se carga directamente desde una URL remota, por lo que se requiere conexión a internet.

## 📦 Dependencias

```
pandas
numpy
matplotlib
seaborn
```

## 📄 Licencia

Este proyecto fue desarrollado con fines académicos en la Universidad Industrial de Santander.
