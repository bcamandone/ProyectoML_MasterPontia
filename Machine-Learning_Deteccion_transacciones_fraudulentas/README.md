## Se quiere desarrollar un sistema capaz de automatizar la tarea de detección de fraude. 

Para ello hará falta seguir los siguientes pasos:
1. Conectarse Y extraer los datos.
2. Llevar a cabo un análisis exploratorio de los datos.
3. Efectuar las tareas de limpieza del dataset necesarias.
4. Si se requiere, utilizar técnicas de data augmentation.
5. Identificar el problema y los objetivos.
6. Fase de selección de datos.
7. Selección del algoritmo.
8. Entrenamiento y parametrización del algoritmo.
9. Evaluación del modelo.
10. Utilizar el modelo de detección de fraude a los datos en producción no etiquetados y generar un archivo con las predicciones. Este archivo debe poseer la siguiente
información: identificador de la transferencia y resultado de la predicción (si es fraudulenta o no).
11. Repetir las fases 5-10 con al menos dos algoritmos de los cuales al menos uno debe ser de Deep Learning y otro no.

Pontia Bank S.L. quiere auditar también estos desarrollos por lo que será necesario entregar uno o varios archivos en los que se registren todas las operaciones realizadas y sus salidas (puede ser un Jupyter Notebook, Google Colab u otro tipo de presentación en el que se pueda ver tanto el código como el resultado de su ejecución). Es preferible, que para poder obtener los mismos resultados si se vuelve a ejecutar, se fije una semilla aleatoria en los distintos algoritmos.


## Model Building
Se aplicaron al caso en particular: 

- Un algoritmo de clasificación, se medirá la recall de los algoritmos: KNN, regresión logística, Naive Bayes y SVC y se entrenará aquel con el cual se obtenga la recall más alta.
- Dos algoritmos de tipo ensemble, Random forest y XGBoost. 
- Un algoritmo de Deep Learnig.

Para este caso en particular las «falsas alarmas» (falsos positivos) no nos preocupan, y lo que queremos evitar son los falsos negativos, por lo tanto, nos interesa una mayor sensibilidad o recall. (VP / + FN VP). También nos interesa la tasa de falsos negativos, llamada también tasa de error, es la probabilidad de que la prueba pase por alto un verdadero positivo. Se calcula como FN / FN + VP, donde FN es el número de falsos negativos y VP es el número de verdaderos
positivos.

