# TelecomX – Predicción de Churn

## Descripción
Este proyecto analiza la cancelación de clientes (Churn) en TelecomX utilizando Python y modelos de machine learning.  
El objetivo es identificar las variables más relevantes asociadas a la cancelación y construir modelos predictivos capaces de anticipar qué clientes tienen mayor probabilidad de abandonar el servicio.

## Tecnologías
- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn
- Google Colab

## Análisis realizado
- Carga y preparación del dataset tratado en la Parte 1
- Eliminación de variables irrelevantes para el modelado
- Transformación de variables categóricas a numéricas
- Análisis de proporción de churn
- Estandarización de variables
- Análisis de correlación
- Visualización de relaciones entre variables clave y churn
- División del dataset en entrenamiento y prueba
- Entrenamiento de modelos predictivos:
  - Regresión Logística
  - Random Forest
- Evaluación con métricas de clasificación
- Análisis de variables más relevantes en la predicción

## Principales hallazgos
Los resultados mostraron que variables como la antigüedad del cliente (`tenure`), el gasto total (`Charges.Total`), el gasto mensual (`Charges.Monthly`), el tipo de contrato y el tipo de servicio de internet tienen una influencia importante en la cancelación.

En general, los clientes con menor antigüedad y contratos más cortos presentaron mayor probabilidad de churn.

## Archivo principal
`TelecomX_LATAM_Parte2.ipynb`

## Autor
Soledad Garcia  
Proyecto realizado como parte del challenge de Alura Latam.
