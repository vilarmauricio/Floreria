# Base de datos Floreria

En este proyecto se realizara la migracion de datos alamacenados en archivos de XLS y XLSX a una base de datos relacional con MySQL.

El proyecto se dividira en diferentes fases:

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

- Iniciamos pruebas de manejo de archivos y ETL con Python. Librerias Pandas (ETL), Pathlib (Directorios y Archivos), xlwings (Libreria Excel)

   ##### etl_excel.ipynb
   ##### manejo_archivos.ipynb

#### Día 3:

- Creamos el esquema basico y funcional de ETL, que sera replicado y adaptado a todos los archivos
- De cada Archivo XLS se obtienen tres archivos CSV (Stock, Precios, Caja)

#### Día 4:

- See semi-automatiza el proceso de ETL obteniendo los CSV de todos los meses del año 2011

    ##### automatizacion_v1.ipynb
