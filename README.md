# Diplodatos2020

## Título del Proyecto: Ciencia de Datos aplicada en la distribución de Energía Eléctrica
### Descripción del dataset, problemas interesantes asociados
Se provee de un dataset que contiene la base de datos geográfica del año 2018 de la empresa ENF (Energisa Nueva Friburgo).
El dataset contiene datos geográficos de los consumidores y de todos los activos de la distribuidora.
Uno de los mayores desafíos de esta industria es conocer los impulsores de la Calidad de Servicio que permitan la toma de dicisiones eficientes sobre los costos operativos e inversiones.
El objetivo de este proyecto es que el estudiante a lo largo de las materias de la diplomatura identifique y aplique diferentes técnicas de análisis/procesamiento de los datos que generen información relevantes para la toma de decisiones.

## Objetivos generales para cada materia:

### Análisis y Visualización
* Correlación entre variables/análisis de independencia. A través de este análisis se debe identificar el impacto de cada variable sobre la calidad de servicio.
* Análisis de outliers.
* Visualización de la calidad de servicio y el consumo de energía anual por grupo tarifario, circuito y por conjunto eléctrico

### Análisis y Curación
Para análisis y curación podrán aplicarse sobre el dataset (en su totalidad) los siguientes puntos:
* Importación de datos.
* Chequeo de claves únicas por sample/eliminar duplicados.
* Despersonalización de datos.
* Normalización de los nombres de las columnas en los dataframes.
* Tratamiento de valores faltantes.
* Codificación de variables categóricas.
* Análisis de valores atípicos.
* Persistencia de los resultados.
* Ordenamiento de las columnas.
* Vinculación de la tablas a través de las llaves de las tablas
* Eliminar columnas que no aporten información.
* Crear un dataset único a partir de las tablas provistas incluyendo toda la información útil en una misma tabla.

### Introducción al ML
El dataset está compuesto por muchas tablas con información geográfica y variables sobre las cuales se puede aplicar análisis y procesamiento. 
El objetivo en este punto es que los estudiantes aprendan a dividir el dataset, a seleccionar el modelo y evaluar las métricas.
Se propone trabajar con tres variables simples de analizar, el consumo anual, el tipo de zona geográfica (urbana o rural) y la cantidad de interrupciones (FIC), y con esto hacer un sistema predictivo en donde se introduce un consumo anual, la zona geográfica y el modelo predice la cantidad de interrupciones. Con esto podrá aplicarse:
* Carga de datos.
* Una pequeña reestructuración de las columnas optimizandolo para el análisis que se desea hacer (por ejemplo considerar el análisis por consumidor o agrupado por categoría tarifaria, o el circuito provista por el dataset).
* División en conjuntos de entrenamiento y evaluación.
* Elección de un modelo.
* Selección de hyperparámetros.
* Métricas sobre el conjunto de evaluación.

### Aprendizaje Supervisado
Para la aplicación de aprendizaje no supervisado sería interesante realizar una Segmentación de la calidad de servicio mediante técnicas de clusterización con las diferentes variables disponibles.
Hacer un análisis de los grupos obtenidos que nos permita evaluar cuales son las variables que mejor explican la calidad de servicio. Estas variables podemos utilizarlas en los algoritmos de aprendizaje supervisado para mejorar su calidad de predicción. Podría utilizarse un algoritmo como K Means con algún método de optimización de número de clusters como elbow method.

### Optativas Relacionadas
Análisis de series temporales, Introducción al aprendizaje profundo.

### Contenido del Dataset
El dataset contiene las informaciones geográficas de la empresa ENF de la ciudad de Nueva Friburgo, en el estado de Rio de Janeiro, Brasil. El documento Módulo10_Revisão0.pdf tiene una descripción detallada del contenido del dataset.

