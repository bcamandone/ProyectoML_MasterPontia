# ProyectoML_MasterPontia

Master en Data Sciencist - Institución: Pontia.tech

El proyecto Júpiter tiene como objetivo principal terminar de unir los conceptos para el alumno de forma práctica, mediante un proyecto que consiste en desarrollar un sistema de detección de transacciones fraudulentas.

El proyecto cuenta con 7 archivos, a continuación se describen los archivos con su contenido:

alarma_fraude.json : archivo donde el sistema almacena un nuevo registro cuando detecta una posible transacción fraudulenta.

balances.json : de cada cliente se almacena una lista con todas sus transacciones (emitidas y recibidas), concretamente el t_id, el balance previo y el balance posterior a la operación.

clientes.json

cuantia.json

tiempo.json : archivo histórico en el que por cada unidad de tiempo se almacena una lista con los t_id que se han producido en dicha unidad de tiempo

tipo.json

es_fraude.json : archivo que almacena el etiquetado manual (que indica si son fraudulentas) de todas las transacciones, a excepción de los datos en producción no etiquetados que deben predecirse (los t_id de estas operaciones no aparecen en este archivo)
