Los arboles de decisión son estructuras de datos que se pueden utilizar para establecer un conjunto de reglas de decisión que pueden ser representadas de manera visual mediante nodos, ramas y hojas.
Todos los nodos representan una única variable y los nodos terminales (las hojas), representan la decisión final del algoritmo, esto quiere decir el valor que devolverá al final de la ejecución.

Los algoritmos más utilizados para crear arboles de decisión son:

ID3: Utiliza la entropía y ganancia de información. Con base en la variable objetivo, seleccionando las particiones que ofrezcan mayor ganancia de información, para realizar la partición entre nodo padre y nodos hijos.

Índice de Gini: Usado solamente para conjuntos de datos en los que la variable objetivo es binaria, usando el método CART (Classification and Regressión Trees).  Consiste en seleccionar el Split con menor Gini ponderado para realizar la partición entre el nodo padre y los nodos hijos.

CHAID: Puede tener más de dos categorías como variable objetivo, utiliza el estadístico Chi Cuadrado para probar la hipótesis nula que dos variables son independientes, para encontrar la dependencia entre la variable del split y la variable de la clase, para establecer la partición.

Reducción de la Varianza: Usado cuando la variable objetivo es continua. El algoritmo calcula la varianza de cada nodo y toma el promedio de la varianza para decidir los subnodos.
