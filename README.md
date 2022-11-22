# Base de datos Florería

En este proyecto se realizara la migración de datos almacenados en archivos de XLS y XLSX a una base de datos relacional con MySQL.

El proyecto se dividirá en diferentes fases:

-	Primera Fase:

Estudio del Negocio y Estructura de los archivos

Armar Estructura básica de Data Warehouse

Lograr un proceso de ETL automatizado

Crear CSV con datos limpios y ordenados

-	Segunda Fase:

Creación y mejoras de Data Warehouse

Crear tablas relacionales con SQL

Ingesta de datos obtenidos del proceso de ETL

-	Tercera Fase:

Realizar los primero Análisis gráficos y Predicciones 

-	Cuarta Fase:

Ingesta y validación de nuevos Datos



### Se planteo una hoja de ruta - Pipeline

![Pipeline](https://github.com/vilarmauricio/Floreria/blob/main/pipeline.jpg)

### Primera Fase:
#### Día 1:

- Se realiza el primer estudio del negocio y requerimientos
- Se estudia estructura y tipos de datos de los archivos

#### Día 2:

- Iniciamos pruebas de manejo de archivos y ETL con Python. Librerías Pandas (ETL), Pathlib (Directorios y Archivos), xlwings (Librería Excel)

   ##### etl_excel.ipynb
   ##### manejo_archivos.ipynb

#### Día 3:

- Creamos el esquema básico y funcional de ETL, que será replicado y adaptado a todos los archivos
- De cada Archivo XLS se obtienen tres archivos CSV (Stock, Precios, Caja)

#### Día 4:

- Se semi-automatiza el proceso de ETL obteniendo los CSV de los meses con los que contamos del año 2011

    ##### automatizacion_v1.ipynb
    
#### Día 5:

- Se realiza la creación de la estructura relacional de la base de datos

#### Día 6:

- Se crea la base de datos y las tablas con sus relaciones definidas con mysql

### Segunda Fase:
#### Día 7: 

- Se realizan prácticas para conexión y manejo de la base de datos con Python

#### Día 8:

- Se trabaja en un nuevo ETL para la ingesta de los datos almacenados en los CSV a la base de datos
