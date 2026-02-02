# Telecom Operator Efficiency Analysis
Identificación de operadores ineficientes en telecomunicaciones mediante análisis de datos, métricas de negocio y validación estadística.
## Contexto de Negocio (Enfoque Data Analyst)
Las operaciones de telecomunicaciones dependen directamente del desempeño de los operadores para garantizar calidad en el servicio, eficiencia operativa y satisfacción del cliente.
Comportamientos ineficientes pueden generar mayores tiempos de respuesta, baja conversión y aumento de costos operativos.

### Objetivo del proyecto:
Identificar operadores ineficientes mediante análisis exploratorio de datos, ingeniería de características y pruebas estadísticas, transformando datos operativos crudos en insights accionables para la toma de decisiones.

## Preguntas Clave del Análisis
¿Qué operadores presentan bajo nivel de actividad de forma consistente?

¿Qué métricas influyen más en la ineficiencia operativa?

¿Existen diferencias estadísticamente significativas entre operadores eficientes e ineficientes?

¿Es posible cuantificar la ineficiencia en un solo indicador?
## Metodología
1. Calidad y Preparación de Datos
Identificación y eliminación de duplicados

Análisis y tratamiento de valores nulos

Normalización de variables temporales

Validación de consistencia de datos

2. Análisis Exploratorio de Datos (EDA)
Distribución de actividad por operador

Patrones de interacción de usuarios

Análisis temporal de desempeño

Correlación entre métricas clave

3. Ingeniería de Características
Indicadores de baja actividad

Métricas de carga y desbalance operativo

Variables relacionadas con conversión

Agregaciones a nivel operador

4. Modelo de Puntaje de Ineficiencia
Se construyó un Inefficiency Score combinando múltiples métricas normalizadas relacionadas con el comportamiento y desempeño de cada operador.

5. Validación Estadística
Pruebas de hipótesis (tests no paramétricos)

Análisis de correlación

Comparación de distribuciones entre grupos de operadores
## Principales hallazgos
El subconjunto reducido a operadores con llamadas peridas, representan el 98% de los operadores ineficientes.
El desempeño del operador esta altamente relacionado al usuario, esto por rotacion de personal y distribucion del trabajo.
