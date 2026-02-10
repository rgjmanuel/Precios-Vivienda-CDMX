# Precios-Vivienda-CDMX
Repositorio con un modelo de precios de vivienda para la Ciudad de México, desarrollado en Python. Incluye limpieza de datos, análisis exploratorio y estimación de un Modelo Lineal Generalizado (GLM Gamma con enlace log) para explicar y predecir precios inmobiliarios. 

## Datos
La base de datos contiene información de viviendas, incluyendo variables como:
- superficie construida,
- ubicación geográfica,
- municipio,
- precio de mercado.

Los datos se utilizan exclusivamente con fines analíticos. Fueron obtenidos de https://www.kaggle.com/datasets/allankirwa/mexico-city-real-estate-dataset

## Metodología
Se evaluaron múltiples especificaciones del modelo.  
El modelo final corresponde a una regresión GLM con distribución Gamma y función de enlace log, seleccionada con base en:
- criterios estadísticos (ajuste, significancia y estabilidad),
- coherencia económica e inmobiliaria de los coeficientes.

El modelo está orientado principalmente a **predicción**, no a inferencia causal.

## Resultados
El modelo permite estimar precios de vivienda de forma consistente con la teoría económica del mercado inmobiliario y captura adecuadamente la heterogeneidad espacial.
