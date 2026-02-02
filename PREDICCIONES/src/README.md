# Predicción de Churn en Clientes de Gimnasio

Análisis end-to-end para identificar clientes con riesgo de abandono (churn) mediante análisis exploratorio, modelos predictivos y segmentación de clientes.

## Contexto del Problema

La retención de clientes es un factor crítico para negocios basados en membresías, como los gimnasios.
El abandono de clientes (churn) impacta directamente en los ingresos y en la estabilidad operativa, por lo que identificar de manera anticipada a los clientes con mayor riesgo de churn permite implementar estrategias de retención más efectivas.

## Objetivo del Proyecto

Desarrollar un análisis de datos de principio a fin que permita:

Comprender el comportamiento de los clientes

Identificar patrones asociados al churn

Construir y evaluar modelos predictivos

Generar insights accionables para apoyar decisiones de negocio orientadas a la retención de clientes

## Metodología
### 1. Carga y Preparación de Datos

Uso de rutas relativas para garantizar reproducibilidad

Limpieza y validación de datos

Preparación de variables numéricas y categóricas

### 2. Análisis Exploratorio de Datos (EDA)

Distribución de churn vs no churn (%)

Análisis de variables relevantes

Correlación entre características

Identificación de patrones de comportamiento

### 3. Preparación de Variables

Separación de variables predictoras (X) y variable objetivo (y)

División del dataset mediante train-test split estratificado para preservar la distribución de clases

### 4. Modelado Predictivo

Se entrenaron y compararon dos modelos:

Regresión Logística

Random Forest

### 5. Evaluación de Modelos

Los modelos se evaluaron utilizando métricas adecuadas para problemas de churn:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Dado el desbalance entre clases, se priorizó el análisis de Recall y F1-score para evaluar la correcta detección de clientes en riesgo.

### 6. Segmentación de Clientes

Aplicación de técnicas de clustering

Identificación de segmentos con diferentes niveles de propensión al churn

Análisis del comportamiento de cada grupo

## Principales Insights

El churn representa una proporción significativa de los clientes, justificando un enfoque analítico orientado a la detección temprana.

El modelo de Random Forest mostró un mejor balance entre precisión y capacidad de detección de churn en comparación con la Regresión Logística.

La segmentación de clientes permitió identificar grupos con mayor riesgo de abandono, los cuales pueden ser priorizados para estrategias de retención específicas.

## Conclusión

A través de un análisis end-to-end, se identificaron patrones clave asociados al abandono de clientes mediante técnicas de análisis exploratorio, modelado predictivo y segmentación.

El uso de métricas adecuadas para un problema de churn permitió evaluar correctamente el desempeño de los modelos, destacando a Random Forest como la alternativa con mejor equilibrio entre precisión y detección de clientes en riesgo.
Adicionalmente, la segmentación de clientes reveló grupos con comportamientos diferenciados, ofreciendo oportunidades claras para implementar estrategias de retención focalizadas.

Este proyecto demuestra cómo el análisis de datos y los modelos predictivos pueden transformar datos operativos en insights accionables, apoyando la toma de decisiones estratégicas orientadas a reducir el churn y mejorar el valor del cliente.
