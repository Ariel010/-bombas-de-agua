# -bombas-de-agua
CLASIFICACIÓN BINARIA DE PUNTOS DE AGUA, ENTRE  FUNCIONALES Y NO FUNCIONALES

#### Proyecto: Clasificación Binaria de Puntos de Agua en Tanzania

Introducción

Este proyecto forma parte de un reto grupal desarrollado en el marco del programa de la Escuela de Talento Digital de la Fundación NTT DATA. El objetivo es predecir qué bombas de agua en Tanzania son funcionales y cuáles no, utilizando un dataset obtenido del Ministerio de Agua de Tanzania a través de Driven Data.

Descripción del Proyecto

El dataset contiene información sobre varios aspectos de los puntos de agua, como la altitud, el financiador, la organización que instaló el pozo, coordenadas GPS, calidad del agua, entre otros. Este proyecto se compone de varios ejercicios que abarcan desde el análisis exploratorio de datos hasta la implementación de modelos de machine learning para la clasificación de los puntos de agua.

Contenido del Proyecto

Ejercicio 1: Análisis Exploratorio de Datos

Cargamos el archivo reto_agua.csv que contiene los datos.
Mostramos los primeros 5 registros del dataset.
Realizamos un análisis para identificar columnas innecesarias, datos nulos y valores anómalos.
Convertimos las variables categóricas a numéricas y categóricas utilizando técnicas adecuadas.
Entrenamiento del Modelo
Separamos los datos en variables independientes y la variable objetivo (target).
Dividimos el dataset en 80% para entrenamiento y 20% para prueba, con random_state=42.
Entrenamos varios modelos y seleccionamos el que mejor rendimiento tiene basado en el conjunto de prueba.
Selección de Variables
Identificamos las 21 variables que más influyen en la predicción.
Entrenamos el modelo nuevamente con las variables seleccionadas y evaluamos si mejora el rendimiento.
Calculamos y analizamos las métricas de accuracy, precision, y recall para evaluar la efectividad del modelo.
Análisis de Correlación y Outliers
Validamos la correlación entre variables seleccionadas y la variable objetivo mediante gráficos.
Utilizamos métodos gráficos y el método de Inter cuartil para detectar y eliminar outliers en las columnas population y gps_height.
Aplicamos búsqueda de hiperparámetros para ajustar el modelo seleccionado y mejorar su rendimiento.

Cómo Ejecutar el Proyecto

Prerequisitos:

Python 3.x
Jupyter Notebook
Bibliotecas: pandas, numpy, scikit-learn, matplotlib, seaborn

Ejecución:

Clonar el repositorio
Navegar al directorio del proyecto
Ejecutar Jupyter Notebook

#### Resultados y Conclusiones

Este proyecto nos ha permitido no solo desarrollar habilidades técnicas en el análisis de datos y machine learning, sino también colaborar en equipo, documentar alternativas y tomar decisiones basadas en consenso. A través de este enfoque, hemos podido identificar qué puntos de agua en Tanzania son más propensos a fallar, lo cual es crucial para mejorar las operaciones de mantenimiento y garantizar el acceso a agua limpia y potable en las comunidades.