# Beneficios de Seguros – Análisis y Predicción con Machine Learning

**Descripción del Proyecto**

Este proyecto analiza datos de clientes de la aseguradora *Sure Tomorrow* con el objetivo de implementar soluciones de machine learning que permitan mejorar procesos de marketing, predicción y protección de datos sensibles. Se utilizan técnicas de clasificación, regresión, análisis de similitud y ofuscación de datos para abordar distintos desafíos del negocio.

**Objetivos**

1. **Identificar clientes similares** a un cliente dado utilizando algoritmos basados en distancias.
2. **Predecir la probabilidad** de que un nuevo cliente reciba una prestación del seguro, comparando modelos reales con un modelo base (dummy).
3. **Estimar la cantidad esperada de beneficios** que podría recibir un cliente nuevo mediante regresión lineal.
4. **Aplicar ofuscación de datos personales** (protección de privacidad) garantizando que el rendimiento de los modelos no se vea afectado.

**Técnicas y Modelos Utilizados**

- K-Nearest Neighbors (KNN)
- Regresión logística
- Regresión lineal
- Modelos dummy para comparación
- Métricas de evaluación: `accuracy`, `precision`, `recall`, `f1_score`, `roc_auc`, `RMSE`, `R²`
- Análisis de correlación y escalado de características (`StandardScaler`, `MinMaxScaler`, `MaxAbsScaler`)
- Matrices de confusión, curvas ROC, y visualización de resultados

**Ofuscación de Datos**

Se implementa un método basado en álgebra lineal para enmascarar la información personal mediante transformaciones matriciales. El algoritmo protege los datos sin sacrificar el desempeño de los modelos predictivos.

**Conclusiones**

- El modelo de regresión logística mejora significativamente el desempeño frente al modelo dummy.
- La regresión lineal es capaz de estimar de forma razonable el número de prestaciones.
- La ofuscación mediante transformación lineal preserva el rendimiento del modelo, permitiendo protección de datos sin pérdida de calidad predictiva.

**Autor**

Gabriel G. M. – Data Scientist & Electric Engineer 

