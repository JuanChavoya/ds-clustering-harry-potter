# Data

Este directorio contiene los archivos de datos utilizados en el proyecto **Clustering de personajes de Harry Potter**.

## Descripción de los datos

El conjunto de datos incluye información estructurada sobre personajes del universo de *Harry Potter*, con variables relacionadas con:

- Características generales del personaje  
- Afiliación a casas y bandos  
- Participación en eventos relevantes  
- Métricas derivadas utilizadas para análisis exploratorio y clustering  

El dataset fue utilizado como insumo principal para realizar:

- Análisis Exploratorio de Datos (EDA)
- Preparación y limpieza de variables
- Selección y transformación de variables numéricas
- Modelos de clustering no supervisado (K-Means)
- Interpretación de patrones y perfiles de personajes

## Archivos incluidos

- `harry_potter_data.csv`  
  Dataset principal utilizado a lo largo del proyecto.

## Consideraciones sobre el tamaño de los datos

El archivo CSV tiene un tamaño considerable, por lo que:

- Se recomienda cargarlo utilizando rutas relativas desde el notebook.
- En entornos con recursos limitados, es conveniente verificar tipos de datos y valores nulos antes del análisis.
- El procesamiento completo se realiza dentro del notebook principal del proyecto.

## Uso dentro del proyecto

El flujo típico de uso del dataset es:

1. Carga del archivo CSV desde este directorio.
2. Limpieza de valores nulos y eliminación de variables irrelevantes.
3. Selección de variables numéricas para análisis exploratorio.
4. Aplicación de técnicas de clustering.
5. Análisis e interpretación de los clusters obtenidos.

Toda la lógica de procesamiento y análisis se encuentra documentada en los notebooks del proyecto.

## Nota

Los datos se utilizan exclusivamente con fines académicos y de demostración como parte de un proyecto de portafolio en Ciencia de Datos.
