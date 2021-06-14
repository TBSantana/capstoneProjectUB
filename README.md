# capstoneProjectUB

El objetivo del Proyecto es intentar predecir la ocupación de los Airbnb en la ciudad Barcelona en el verano de 2021, utilizando de datos de ocupación de Airbnb en Barcelona desde enero de 2019 hasta abril de 2021 y datos de la evolución de la COVID-19 en Catalauña. 

Organización del repositorio:

1. Carpeta DATA
-Backup: datos en bruto extraídos de http://insideairbnb.com/get-the-data.html + datos anteriores facilitados por los administradores de la página. Añadidos datos de casos de COVID desde marzo de 2020 (Cataluña).
-Processed: dataset procesado, resultado de los procesos de Cleaning y Transformation de los notebooks comentados a continuación.

2. Carpeta SRC

Incluye todo el código que hemos utilizado. Cada notebook incluye anotaciones explicativas del proceso seguido.
Trabajo sobre los datos para 

2.1. Carpeta Cleaninung

 - Agregación de los datos
 - Eliminación de los missing values
 - Cleaning del dataset

2.2. Carpeta Transform (data engineering)
 - Creación de nuevas features en el dataset

2.3. Carpeta Train

Modelos utilziados:

 - Prueba con XGBoost sin hyperparametros
 - Prueba con XGBoost con hyperparametros (resultados no muy buenos)
 - Prueba con RNN (Pytorch) sin hyperparametros
 - Prueba con RNN (Pytorch) con hyperparametros (mejores resultados)

4. Carpeta EDA (exploratory data anaylisis)

- Se incluyen algunas visualizaciones de los datos. 
En la presentación se incluirán más visualizaciones explicativas y otros análisis de los datos y los resultados obtenidos. 



(A eliminar antes de la entrga
Morts per covid mensuals a catalunya (https://dadescovid.cat/diari):

- 21/5: 242
- 21/4: 543
- 21/3: 603
- 21/2: 1096
- 21/1: 2164
- 20/12: 1264
- 20/11: 1828
- 20/10: 914
- 20/9: 364
- 20/8: 296
- 20/7: 179
- 20/6: 195
- 20/5: 1282
- 20/4: 7424
- 20/3: 3697

)

