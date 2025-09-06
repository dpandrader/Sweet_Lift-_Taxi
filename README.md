🚖 Proyecto – Predicción de Pedidos de Taxi mediante Series Temporales

Objetivo del proyecto:

Desarrollar un modelo de predicción que estime la cantidad de pedidos de taxis en aeropuertos para la próxima hora, con el fin de ayudar a Sweet Lift Taxi a atraer más conductores durante las horas pico. El requisito principal era lograr un RECM (RMSE) en test inferior a 48.

Procedimientos:

Exploración y limpieza de los datos históricos de pedidos.
Creación de variables temporales (rezagos, tendencias, estacionalidad).
Entrenamiento y comparación de modelos de forecasting, como regresión lineal, Random Forest y modelos de series temporales.
Ajuste de parámetros y validación para mejorar la precisión del modelo.

Conclusiones:

Se alcanzó un RECM de 45 en el conjunto de prueba, cumpliendo con el objetivo del proyecto.
El modelo permite anticipar la demanda horaria de taxis, facilitando la toma de decisiones estratégicas para la asignación de conductores.
Todo el trabajo se implementó con Python, pandas, scikit-learn, statsmodels y matplotlib.

