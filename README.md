# Time-Series-Project---Taxi-requests

El objetivo del proyecto es construir un modelo de Machine Learning capaz de predecir la cantidad de pedidos de taxis para la próxima hora, usando datos históricos de la empresa Sweet Lift Taxi. Esto permitirá atraer a más conductores en horarios de alta demanda.

📊 Datos:
Dataset: taxi.csv

Variable objetivo: num_orders (número de pedidos)

Se trabajó con una serie temporal con datos de fecha-hora (datetime) y número de pedidos.

🔧 Procesamiento:
Se convierte la columna datetime en índice temporal y se verifica el orden cronológico.

Se realiza resampleo por hora para estructurar la serie temporal correctamente.

Se analiza la estacionalidad y tendencia usando seasonal_decompose.

🤖 Modelado:
Se entrenan distintos modelos de regresión:

Regresión Lineal

Árbol de Decisión

Random Forest

Se realiza validación cruzada y ajuste de hiperparámetros.

División del conjunto en entrenamiento y prueba (10% del total para test).

🎯 Métrica de Evaluación:
RMSE (Root Mean Squared Error) es la métrica clave.

El objetivo es mantener RMSE menor a 48 en el conjunto de prueba.

✅ Resultados y Conclusiones:
El modelo final logra una predicción precisa con un RMSE dentro del umbral esperado.

El modelo puede ser implementado para anticipar la demanda horaria de taxis y tomar decisiones operativas más eficientes.
