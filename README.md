# Clustering de Personajes de Harry Potter

---

## Objetivo del proyecto

Explorar si es posible **segmentar personajes** de la saga de *Harry Potter* en grupos coherentes utilizando técnicas de clustering, basándose en:

- Características generales del personaje  
- Variables emocionales y narrativas  
- Información derivada del dataset original  

El enfoque busca responder preguntas como:

- ¿Existen perfiles de personajes con patrones similares?
- ¿Qué emociones o rasgos dominan en cada grupo?
- ¿Cómo pueden interpretarse estos clusters desde un punto de vista analítico y narrativo?

---

## Metodología

El proyecto sigue un flujo estándar de Ciencia de Datos:

1. **Carga y exploración inicial de datos**
2. **Análisis Exploratorio de Datos (EDA)**
   - Distribuciones
   - Correlaciones
   - Identificación de variables relevantes
3. **Limpieza y preparación**
   - Eliminación de variables irrelevantes
   - Selección de variables numéricas
   - Normalización de datos
4. **Modelado**
   - Aplicación de K-Means
   - Evaluación del número óptimo de clusters
5. **Interpretación**
   - Análisis de características dominantes por cluster
   - Identificación de personajes representativos

---

## Tecnologías utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Estructura del repositorio

```text
├── data/
│   ├── harry_potter_data.csv
│   └── README.md
│
├── notebooks/
│   └── Harry_Potter_Clustering_portfolio.ipynb
│
└── README.md

