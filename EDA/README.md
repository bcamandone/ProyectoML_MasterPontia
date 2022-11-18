# EDA (Exploratory data analysis /  Análisis exploratorio de datos)

Se realiza un análisis exploratorio de datos sobre el conjunto de datos de las transacciones con tres objetivos principales:

1)Entender mejor el problema de negocio que se está intentando solucionar.

2)Encontrar imperfecciones en los datos que nos indiquen que debemos volver a la etapa de extracción de datos e incorporar mejoras.

3)Extraer conclusiones sobre qué variables pueden tener una mayor importancia en el problema a modelar


Identificación de errores e incidencias 

Para este objetivo, Pontia Bank S.L. quiere identificar los datos erróneos que se encuentren entre los proporcionados (un ejemplo es si el balance del cliente aumenta, o disminuye, con la misma cantidad que indica la cuantía). Con el fin de lograrlo, será necesario aplicar el conocimiento que se tiene del negocio, así como las reglas de negocio que la empresa nos ha dado:

• El límite de la retirada en efectivo es de 2000 € al día. 
• El límite de pago con tarjeta de débito al mes es de 5000 €. 
• No se pueden producir tres transferencias en una misma hora. 
• No se pueden producir varias transferencias que juntas sumen más de 3000€ en una misma hora. 

Además de estos errores e incidencias que se pueden detectar, resulta necesario identificar aquellos valores nulos que aparezcan y detectar si existen características comunes de los errores, incidencias y valores nulos del mismo tipo. 
