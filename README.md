# proyecto_analisis_data
 Análisis de Airbnb en Bogotá

Proyecto de análisis de datos sobre alojamientos de Airbnb en Bogotá, Colombia. Se aplicaron técnicas de limpieza, análisis estadístico, visualización y aprendizaje automático.

🎯 Objetivo

Determinar qué factores influyen en el desempeño de una propiedad de Airbnb, teniendo en cuenta principalmente:

- Precio
- Ocupación
- Calificación
- Tipo de propiedad
- Ubicación
- Amenidades
- Características del anfitrión

📂 Estructura del repositorio

analisis-datos/
│
├── README.md
│
├── data/
│ └── airbnb_bogota_limpio.csv
│
└── notebooks/
    └── Proyecto_final_Airbnb.ipynb

🔎 Metodología

El proyecto se desarrolló en las siguientes etapas:

1. Exploración inicial de los datos.
2. Limpieza y transformación del dataset.
3. Análisis estadístico descriptivo.
4. Visualización de los datos.
5. Pruebas estadísticas.
6. Construcción de modelos predictivos.
7. Evaluación de resultados.

🤖 Modelos

Se utilizaron:

- Regresión lineal para analizar el comportamiento del rating.
- Regresión logística multinomial para clasificar el nivel de ocupación en categorías Baja, Media y Alta.

El modelo de clasificación obtuvo una exactitud aproximada del 82,4 %.

🛠️ Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

▶️ Ejecución

El proyecto puede ejecutarse desde el notebook:

"notebooks/Proyecto_final_Airbnb.ipynb"

Los datos utilizados se encuentran en:

"data/airbnb_bogota_limpio.csv"

También puede ejecutarse en Google Colab, cargando previamente el dataset.

📊 Resultados

El análisis muestra que el desempeño de una propiedad no depende únicamente del precio. Factores como la ubicación, tipo de alojamiento, amenidades, características de la propiedad y calificaciones también están relacionados con su comportamiento.

El análisis completo, código, gráficos y resultados se encuentran en el notebook.

📚 Fuente de datos

Los datos utilizados fueron obtenidos de Inside Airbnb.

👥 Autores

Data Experience G4

- Eimy Nicolle Rubio
- Laura Torres
- Juan Esteban Melo
- Juan Serrano

