# fraude
En este proyecto se evaluaron distintos algoritmos de clasificación (KNN, XGBoost y Random Forest) aplicados a un problema con datos desbalanceados, donde el objetivo principal es detectar posibles casos de fraude.

El análisis busca comparar el desempeño de los modelos y entender sus fortalezas:

KNN mostró limitaciones al trabajar con datos desbalanceados.

XGBoost y Random Forest lograron identificar patrones de forma más eficiente y ofrecieron mejores resultados.

Para la validación se utilizó la métrica ROC-AUC, con énfasis en la importancia de reducir los falsos negativos (casos de fraude no detectados), ya que representan un riesgo financiero directo para la institución. Por su parte, los falsos positivos, aunque generan incomodidad en la experiencia del usuario, tienen un impacto económico menor.

Este repositorio concentra el código, visualizaciones y conclusiones clave que permiten entender cómo diferentes modelos de machine learning pueden apoyar en la detección de fraude y la toma de decisiones estratégicas.
