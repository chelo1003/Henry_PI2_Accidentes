# Proyecto Análisis de Datos - Accidentes Viales CABA

Este proyecto consiste en realizar un Análisis de Datos de accidentes viales de la Ciudad Autónoma de Buenos Aires y una presentación de los insights encontrados.
Los datos, disponibles desde el siguiente enlace: [Accidentes Buenos Aires](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales), se tratan de dos archivos en formato Excel con dos hojas de datos en cada uno. El primero de ellos abarca los muertos en 616 accidentes viales entre 2016 y 2021, y el segundo abarca los lesionados en 23.785 accidentes, entre 2019 y 2021.

## Análisis Exploratorio de Datos

El análisis exploratorio de datos está dividido en dos secciones diferentes.  
La primera es la parte de transformaciones ([Enlace al Cuaderno](EDA/2_EDA_transformaciones.ipynb)), donde se revisan los valores nulos y faltantes, se normalizan las fechas, se transforman a enteros las variables numéricas. Se eligen y transcriben a columnas finales los distintos datos de ubicación y los datos sobre los vehículos participantes en los accidentes, que se encuentran divididos entre varias columnas distintas. Es decir, se prepara el dataset para poder realizar el análisis en conjunto del mismo.  
La segunda etapa del EDA es la del análisis propiamente dicho ([Enlace al Cuaderno](EDA/3_EDA_analisis.ipynb)). Se comienza con el estudio de cada una de las variables en forma individual, para luego pasar a combinarlas y buscar insights que nos lleven a identificar los puntos claves de la problemática de los siniestros viales.
