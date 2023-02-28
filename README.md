
# Master en Data Science - Institución: Pontia.tech - Proyecto Jupiter

![banco](https://user-images.githubusercontent.com/86261762/218296884-52227a13-b6ec-4c03-ba97-8dd36c63589c.png)

# Introducción: 

El proyecto Júpiter aborda el estudio de la detección de fraudes en operaciones bancarias mediante algoritmos de Aprendizaje Automático.Este proyecto tiene como objetivo principal terminar de unir los conceptos para el alumno de forma práctica.

La detección de transacciones fraudulentas es un reto debido a dos razones principales: en primer lugar,  los comportamientos “normales” y “fraudulentos” de los usuarios cambian constantemente y, en segundo lugar, los conjuntos de datos de fraude en operaciones bancarias están muy  sesgados (distribución de clases desequilibrada). 


# Problematica: 

La empresa Pontia Bank S.L. necesita desarrollar un sistema de detección de transacciones fraudulentas. Esta compañía, tramita miles de transacciones diarias de todos sus clientes entre las cuales se quiere diferenciar entre las que son fraudulentas de las que no lo son. Para ello, se han extraído las transacciones realizadas en los últimos 30 días (más de 6 millones) e identificado (manualmente) aquellas que son fraudulentas.

Para desarrollar un sistema capaz de automatizar la tarea de detección de fraude hará falta seguir los siguientes pasos:

1) Conectarse Y extraer los datos.
2) Llevar a cabo un análisis exploratorio de los datos.
3) Efectuar las tareas de limpieza del dataset necesarias.
4) Si se requiere, utilizar técnicas de data augmentation.
5) Identificar el problema y los objetivos.
6) Fase de selección de datos.
7) Selección del algoritmo.
8) Entrenamiento y parametrización del algoritmo.
9) Evaluación del modelo.
10) Utilizar el modelo de detección de fraude a los datos en producción no etiquetados y generar un archivo con las predicciones. Este archivo debe poseer la siguiente información: identificador de la transferencia y resultado de la predicción (si es fraudulenta o no).
11) Repetir las fases 5-10 con al menos dos algoritmos de los cuales al menos uno debe ser de Deep Learning y otro no.

Pontia Bank S.L. quiere auditar también estos desarrollos por lo que será necesario entregar uno o varios archivos en los que se registren todas las operaciones realizadas y sus salidas (puede ser un Jupyter Notebook, Google Colab u otro tipo de presentación en el que se pueda ver tanto el código como el resultado de su ejecución). Es preferible, que para poder obtener los mismos resultados si se vuelve a ejecutar, se fije una semilla aleatoria en los distintos algoritmos.


# Descripción de los datos

El proyecto cuenta con 7 archivos json, a continuación se describen los archivos con su contenido:

1) alarma_fraude.json : archivo donde el sistema almacena un nuevo registro cuando detecta una posible transacción fraudulenta.

2) balances.json : de cada cliente se almacena una lista con todas sus transacciones (emitidas y recibidas), concretamente el t_id, el balance previo y el balance posterior a la operación.

3) clientes.json : por cada transaccion nos informa el ID de cliente de origen y el ID de cliente de destino.

4) cuantia.json : Nos informa la cuantia de la transacción por cliente 

5) tiempo.json : archivo histórico en el que por cada unidad de tiempo se almacena una lista con los t_id que se han producido en dicha unidad de tiempo

6) tipo.json :  nos informa el tipo de la transaccion: PAYMENT TRANSFER CASH_OUT DEBIT CASH_IN

7) es_fraude.json : archivo que almacena el etiquetado manual (que indica si son fraudulentas) de todas las transacciones, a excepción de los datos en producción no etiquetados que deben predecirse (los t_id de estas operaciones no aparecen en este archivo)

