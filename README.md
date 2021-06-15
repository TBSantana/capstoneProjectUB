# capstoneProjectUB

El objetivo del Proyecto es intentar predecir la ocupación de los Airbnb en la ciudad Barcelona en el verano de 2021, utilizando de datos de ocupación de Airbnb en Barcelona desde enero de 2019 hasta abril de 2021 y datos de la evolución de la COVID-19 en Catalauña. Se analizará la evolución de la ocupación y las diferencias que se observan entre la situación pre-pandemia y la situación actual. 

Organización del repositorio:

## 1. Carpeta DATA

-Backup: datos en bruto extraídos de http://insideairbnb.com/get-the-data.html + datos anteriores facilitados por los administradores de la página. Añadidos datos de casos de COVID desde marzo de 2020 (Cataluña).

-Processed: dataset procesado, resultado de los procesos de Cleaning y Transformation de los notebooks comentados a continuación. El dataset final usado en los modelos es listings_transformed.csv
Se incluye también un archivo geojson utilizado para visualizaciones, y el Data Dictionary de los datos de Airbnb.

## 2. Carpeta SRC

Incluye todo el código que hemos utilizado. Cada notebook incluye anotaciones explicativas del proceso seguido.
Trabajo sobre los datos para 

### 2.1. Carpeta Cleaning

 - Agregación de los datos
 - Eliminación de los missing values
 - Cleaning del dataset

### 2.2. Carpeta Transform (data engineering)
 - Creación de nuevas features en el dataset

### 2.3. Carpeta Train

Modelos utilziados:

 + Prueba con XGBoost sin hyperparametros
 + Prueba con XGBoost con hyperparametros (resultados no muy buenos)
 + Prueba con RNN (Pytorch) sin hyperparametros
 + Prueba con RNN (Pytorch) con hyperparametros (mejores resultados)

## 2.4. Carpeta EDA (exploratory data anaylisis)

- Se incluyen algunas visualizaciones de los datos, de las que extraer conclusiones.
En la presentación se incluirán más visualizaciones explicativas y otros análisis de los datos y los resultados obtenidos. 


Autores:

+ Míriam Potau

+ Thayane Santana

+ Sara Pereira

+ Pol Paniagua
