# ProyectoML_MasterPontia

Master en Data Sciencist - Institución: Pontia.tech

El proyecto Júpiter tiene como objetivo principal terminar de unir los conceptos para el alumno de forma práctica, mediante un proyecto que consiste en desarrollar un sistema de detección de transacciones fraudulentas.

El proyecto cuenta con 7 archivos json, a continuación se describen los archivos con su contenido:

1) alarma_fraude.json : archivo donde el sistema almacena un nuevo registro cuando detecta una posible transacción fraudulenta.

2) balances.json : de cada cliente se almacena una lista con todas sus transacciones (emitidas y recibidas), concretamente el t_id, el balance previo y el balance posterior a la operación.

3) clientes.json : por cada transaccion nos informa el ID de cliente de origen y el ID de cliente de destino.

4) cuantia.json : Nos informa la cuantia de la transacción por cliente 

5) tiempo.json : archivo histórico en el que por cada unidad de tiempo se almacena una lista con los t_id que se han producido en dicha unidad de tiempo

6) tipo.json :  nos informa el tipo de la transaccion: PAYMENT TRANSFER CASH_OUT DEBIT CASH_IN

7) es_fraude.json : archivo que almacena el etiquetado manual (que indica si son fraudulentas) de todas las transacciones, a excepción de los datos en producción no etiquetados que deben predecirse (los t_id de estas operaciones no aparecen en este archivo)
