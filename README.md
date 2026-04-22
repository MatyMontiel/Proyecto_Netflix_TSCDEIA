# Proyecto_Netflix_TSCDEIA
Análisis de datos de una plataforma tipo Netflix utilizando un dataset integrado.

## Descripción
Este proyecto tiene como objetivo analizar el comportamiento de usuarios en una plataforma de streaming similar a Netflix, utilizando un conjunto de datos sintético que representa interacciones reales dentro del sistema.

Se trabaja con múltiples fuentes de datos (usuarios, contenido, historial de visualización, búsquedas, reseñas y recomendaciones), las cuales fueron integradas para construir un dataset unificado que permita su análisis.

## Objetivo
El análisis se orienta a comprender patrones de uso de los usuarios y, particularmente, a explorar factores asociados a la actividad o abandono dentro de la plataforma.

## Dataset
El dataset original está compuesto por seis tablas relacionadas. A partir de estas, se generó un archivo unificado en formato CSV que consolida la información relevante a nivel usuario.

Este dataset cumple con los requisitos de la materia, incluyendo una combinación de variables cualitativas y cuantitativas, y una cantidad suficiente de registros para realizar análisis estadístico.

## Estructura del repositorio
## Estructura del repositorio

```
PROYECTO_NETFLIX_TSCDEIA/
│
├── Datos/
│   ├── dataset_unificado.csv
│   ├── users.csv
│   ├── movies.csv
│   ├── watch_history.csv
│   ├── reviews.csv
│   ├── search_logs.csv
│   └── recommendation_logs.csv
│
├── docs/
│   └── descripcion_problema.md
│
└── README.md
```


## Proceso realizado
* Selección del dataset
* Identificación de fuentes de datos
* Integración de tablas mediante claves comunes
* Construcción de un dataset unificado
* Preparación para análisis exploratorio y estadístico

## Próximos pasos
* Análisis exploratorio de datos
* Visualización de patrones
* Aplicación de estadística descriptiva
* Análisis inferencial

## Notas
El dataset utilizado es de carácter sintético, por lo que no contiene información sensible de usuarios reales. Sin embargo, se respetan buenas prácticas en el manejo y análisis de datos.
