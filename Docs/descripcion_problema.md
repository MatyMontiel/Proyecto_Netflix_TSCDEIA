# Comprensión del problema

## Descripción del problema
En la actualidad, las plataformas de streaming generan grandes volúmenes de datos a partir de la interacción de los usuarios con el contenido. Analizar estos datos permite comprender mejor el comportamiento de los usuarios y mejorar la toma de decisiones dentro del negocio.

En este proyecto se aborda el análisis del comportamiento de usuarios en una plataforma de streaming tipo Netflix, con el objetivo de identificar patrones de uso, preferencias de consumo y diferencias entre distintos perfiles de usuarios.

Uno de los principales desafíos en este tipo de plataformas es detectar cuándo un usuario deja de utilizar el servicio y entender qué factores pueden estar asociados a este comportamiento.

## Definición del problema de negocio
El problema de negocio seleccionado es el análisis del abandono de usuarios (*churn*).

La pregunta principal que guía el análisis es:

**¿Qué características y comportamientos diferencian a los usuarios activos de aquellos que dejan de utilizar la plataforma?**

Este problema es relevante ya que permite identificar patrones asociados a la pérdida de usuarios y, en etapas futuras, podría contribuir al desarrollo de estrategias de retención.

La elección de este enfoque se fundamenta en la disponibilidad de una variable objetivo (`is_active`) y en la existencia de múltiples variables relacionadas al comportamiento del usuario.

## Identificación de fuentes de datos
Para el desarrollo del proyecto se utilizaron múltiples fuentes de datos que, en conjunto, representan el funcionamiento de una plataforma de streaming.

El dataset original está compuesto por seis tablas relacionadas:

* **users.csv**: contiene información demográfica y de suscripción de los usuarios, incluyendo la variable `is_active`.
* **movies.csv**: incluye información sobre el contenido disponible (género, duración, características).
* **watch_history.csv**: registra el historial de visualización y permite analizar el comportamiento de consumo.
* **reviews.csv**: contiene reseñas y calificaciones realizadas por los usuarios.
* **search_logs.csv**: registra las búsquedas realizadas dentro de la plataforma.
* **recommendation_logs.csv**: incluye información sobre las recomendaciones y la interacción con ellas.

Estas fuentes se relacionan principalmente mediante las claves `user_id` y `movie_id`, lo que permite su integración.

A partir de estas tablas se construyó un dataset unificado en formato CSV para facilitar el análisis.

## Tipos de variables
El dataset final contiene una combinación de variables cualitativas y cuantitativas.

### Variables cualitativas
* user_id
* gender
* subscription_plan
* is_active

### Variables cuantitativas
* age
* monthly_spend
* household_size
* total_sessions
* avg_watch_duration
* avg_progress_pct
* total_reviews
* avg_review_rating
* total_searches
* rec_click_rate

Esta combinación permite aplicar tanto análisis descriptivos como inferenciales.

## Metadatos
* **Origen de los datos**: Dataset sintético que simula una plataforma de streaming
* **Formato**: CSV
* **Unidad de análisis**: Usuario
* **Periodo temporal**: Datos simulados correspondientes a interacciones entre 2024 y 2025
* **Frecuencia de actualización**: No aplica
* **Tipo de datos**: Estructurados

## Consideraciones éticas
El dataset utilizado es de carácter sintético, por lo que no contiene información personal real ni sensible. Sin embargo, el análisis se realiza respetando buenas prácticas en el manejo de datos.

Además, se consideran aspectos como la presencia de valores faltantes, duplicados y outliers, los cuales forman parte de escenarios reales y deben ser tratados adecuadamente en etapas posteriores del análisis.