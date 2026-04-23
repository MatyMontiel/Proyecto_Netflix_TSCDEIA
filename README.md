# Proyecto_Netflix_TSCDEIA
Análisis de datos de una plataforma tipo Netflix utilizando un dataset integrado.

## Integrantes
Estudiantes de la carrera Ciencia de Datos e Inteligencia Artificial:

* **Marovich, Miakel.** — DNI: 41.625.321 — — [dmmarovich4@gmail.com] (Cuenta de GitHub)
* **Molina, Lorenzo** — DNI: 41.712.829 — — [molinaplorenzo@gmail.com] (Cuenta de GitHub)
* **Montiel, Matias** — DNI: 42.474.994 — [axel-gta4@hotmail.com] (Cuenta de GitHub)
* **Munighini, Antonella** — DNI: 44.194.338 — — [antonellamunighini.a@gmail.com] (Cuenta de GitHub)
* **Villarruel, Tomás** — DNI: 44.896.222 — — [tomasvillarruel18@gmail.com] (Cuenta de GitHub)


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
* Limpieza
* Estandarizacion de datos

## Notas
El dataset utilizado es de carácter sintético, por lo que no contiene información sensible de usuarios reales. Sin embargo, se respetan buenas prácticas en el manejo y análisis de datos.
