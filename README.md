# TelecomX – Predicción de Churn

Proyecto de análisis de datos orientado a identificar factores asociados a la cancelación de clientes.

El objetivo fue analizar el comportamiento de clientes de TelecomX y construir modelos predictivos que permitan estimar qué clientes tienen mayor probabilidad de abandonar el servicio.

---

## Objetivo del proyecto

- Analizar la cancelación de clientes, también conocida como churn.
- Identificar variables relevantes relacionadas con la baja de clientes.
- Preparar los datos para aplicar modelos de clasificación.
- Comparar el desempeño de distintos modelos predictivos.
- Extraer conclusiones útiles para la toma de decisiones.

---

## Herramientas utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

---

## Proceso de análisis

1. Carga del dataset limpio trabajado en la primera etapa.
2. Revisión y preparación de variables.
3. Eliminación de columnas irrelevantes para el modelado.
4. Transformación de variables categóricas a numéricas.
5. Análisis de proporción de churn.
6. Estandarización de variables.
7. Análisis de correlación.
8. Visualización de variables relevantes.
9. División del dataset en entrenamiento y prueba.
10. Entrenamiento de modelos de clasificación.
11. Evaluación de resultados.
12. Análisis de variables con mayor influencia en la predicción.

---

## Modelos aplicados

- Regresión Logística
- Random Forest

---

## Principales hallazgos

El análisis mostró que algunas variables tienen una relación importante con la cancelación de clientes:

- Antigüedad del cliente
- Gasto total
- Gasto mensual
- Tipo de contrato
- Tipo de servicio de internet

En general, los clientes con menor antigüedad y contratos más cortos presentaron mayor probabilidad de churn.

---

## Conclusión

Este proyecto permitió aplicar un flujo completo de análisis de datos y modelado predictivo: desde la preparación del dataset hasta la evaluación de modelos.

Además, permitió identificar patrones de comportamiento asociados a la cancelación de clientes, lo que puede ayudar a pensar estrategias de retención y seguimiento comercial.

---

## Archivos del repositorio

- `Challenge_TelecomX_Parte2.ipynb`: notebook principal del análisis.
- `telecomx_parte1_limpio (1).csv`: dataset limpio utilizado para el modelado.
- `README.md`: documentación del proyecto.

---

## Autor

**Soledad García**

Proyecto realizado como parte del challenge de Alura Latam.
