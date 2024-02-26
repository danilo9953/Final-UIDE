# Final-UIDE
Proyecto: Desarrollo de un modelo para predecir en base a ciertas características obtenidas si un paciente puede tener Cáncer de Mama.
Desarrollo:
1.	Se obtiene los datos a procesar en los diferentes modelos.
2.	Se realiza una exploración de las variables y se verifica si hay algún tipo de inconsistencia.
 
3.	Se propone 3 modelos a ser ejecutados: Regresión logística, árbol de decisión y k-NN.
4.	Para cada uno de los modelos se crea la matriz de confusión y la precisión de cada modelo, esto para los datos de entrenamiento y prueba.
Análisis de los resultados de cada modelo:
Previamente se cita que de acuerdo a la predicción que se desea realizar se tomar muy en cuenta los falsos negativos pues para estos casos sería grave este particular. 
•	Regresión logística:
 
Precisión del modelo en los datos de entrenamiento: 0.9868131868131869
Precisión del modelo en los datos de prueba: 0.9736842105263158
A nivel general la precisión del modelo es importante y cercana al 100%, los falsos negativos existen, pero en cantidad mínima y se deben tener especial atención.


•	Árbol de decisión:
 
Precisión del modelo en los datos de entrenamiento: 1.0
Precisión del modelo en los datos de prueba: 0.9298245614035088

Como se puede apreciar el modelo en los datos de entrenamiento no tuvo margen de error, pero en los datos de prueba vemos que la precisión baja un 8%, lo que podría ser una señal de que el modelo está sobreajustado (overfitting). 

•	k-NN:
 
Precisión del modelo en los datos de entrenamiento: 0.9802197802197802
Precisión del modelo en los datos de prueba: 0.9473684210526315

En este modelo si bien en los datos de entrenamiento tiene un 98% de precisión, en valor absoluto tenemos un número alto en falso negativo respecto de los otros modelos. En los datos de prueba baja el número de falsos negativos con el antecedente de los datos de entrenamiento quedan ciertas dudas de si funcionaría adecuadamente.

Decisión final:
En base a los resultados obtenidos de cada modelo, concluyo que el modelo apropiado es la regresión logística, muestran una precisión importante y en los datos de prueba respecto de los falsos negativos es un número bajo. Estimo que al ser este modelo relacionado con temas de salud debería ser actualizado con mas datos por lo menos una vez al año, esto con el fin de poder mejorar el modelo.

 
