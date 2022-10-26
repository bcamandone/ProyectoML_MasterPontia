# Carga de archivos json a jupyter notebook 


 El proyecto cuenta con 7 archivos, a continuación se describen los archivos con su contenido:

1) alarma_fraude.json : archivo donde el sistema almacena un nuevo registro cuando detecta una posible transacción fraudulenta.

2) balances.json : de cada cliente se almacena una lista con todas sus transacciones (emitidas y recibidas), concretamente el t_id, el balance previo y el balance posterior a la operación.

3) clientes.json

4) cuantia.json

5) tiempo.json : archivo histórico en el que por cada unidad de tiempo se almacena una lista con los t_id que se han producido en dicha unidad de tiempo

6) tipo.json

7) es_fraude.json : archivo que almacena el etiquetado manual (que indica si son fraudulentas) de todas las transacciones, a excepción de los datos en producción no etiquetados que deben predecirse (los t_id de estas operaciones no aparecen en este archivo)


En esta primer etapa de lectura de los archivos se utilizaron las librerías: pandas, json y csv.
Mediante el uso de varias sentencias se convirtieron los archivos json a Dataframes con formato tabular, de manera que puedan ser utilizados posteriormente para el analisis exploratorio de datos. 

