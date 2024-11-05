# Descripción del Dataset

Este archivo contiene información general y metadatos acerca del dataset utilizado para el análisis bioinformático.

## Contenido del Dataset

El dataset está compuesto por dos archivos principales:
- **DataValues_S013.csv**: Contiene las mediciones experimentales para cada muestra en el estudio.
- **DataInfo_S013.csv**: Proporciona los metadatos que describen las variables en el archivo de datos.

## Descripción de las Variables Principales

### Archivo `DataValues_S013.csv`
- **SUBJECTS**: Identificación única de cada muestra en el estudio.
- **SURGERY**: Tipo de cirugía asociada a cada sujeto (ej., bypass, tubular, etc.).
- **AGE**: Edad de cada sujeto en años.
- **GENDER**: Género de cada sujeto (F o M).
- **Group**: Identificación del grupo experimental al que pertenece cada sujeto (1 o 2).
- Variables de medición (columnas restantes): Representan diferentes metabolitos o características biológicas de interés. Cada columna contiene los niveles medidos de esa característica para cada muestra.

### Archivo `DataInfo_S013.csv`
- **VarName**: Nombre de cada variable en el dataset de mediciones, que coincide con los nombres de columna en `DataValues_S013.csv`.
- **varTpe**: Tipo de la variable (por ejemplo, "integer", "character").
- **Description**: Descripción de la variable, que detalla qué representa o mide cada una.

## Archivos en el Repositorio

- `informe.html` / `informe.pdf`: Informe generado a partir del script RMarkdown que documenta el proceso de análisis.
- `Molina-Ribagorda-Andres-PEC1.rmd`: Código R que contiene el análisis y exploración de los datos.
- `dataset.Rda`: Objeto contenedor que incluye los datos y metadatos procesados.
- `DataValues_S013.csv` / `DataInfo_S013.csv`: Archivo con los datos originales en formato CSV, sin procesar.
- `README.md`: Este archivo, que describe el propósito del proyecto, los metadatos del dataset y la estructura de los archivos.