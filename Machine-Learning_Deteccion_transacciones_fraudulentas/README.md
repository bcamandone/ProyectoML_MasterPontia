
## Model Building
Se aplicaron al caso en particular: 

- Un algoritmo de clasificación, se medirá la recall de los algoritmos: KNN, regresión logística, Naive Bayes y SVC y se entrenará aquel con el cual se obtenga la recall más alta.
- Dos algoritmos de tipo ensemble, Random forest y XGBoost. 
- Un algoritmo de Deep Learnig.

Para este caso en particular las «falsas alarmas» (falsos positivos) no nos preocupan, y lo que queremos evitar son los falsos negativos, por lo tanto, nos interesa una mayor sensibilidad o recall. (VP / FN  + VP). También nos interesa la tasa de falsos negativos, llamada también tasa de error, es la probabilidad de que la prueba pase por alto un verdadero positivo. Se calcula como (FN / FN + VP), donde FN es el número de falsos negativos y VP es el número de verdaderos
positivos.

