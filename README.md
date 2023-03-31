# Pancakes Profundidad

&emsp; Este programa resuelve el problema de pancake sorting mediante el uso de DFS (Depth First Search) o busqueda por profundidad.

&emsp; **Lenguaje utilizado**: Python

## Funciones

 ### &emsp;**'__ init __(self, pancakes, profundidad)'**
 &emsp; Este el constructor de la clase Pancakes que recibe como parametros una lista de letras desordenadas y una profundidad limite para el  
 &emsp; programa.
 ### &emsp;**'voltear(self, posicion, pancakes)'**
 
&emsp; Esta funcion recibe como parametro la posición donde se van a voltear los pancakes y la lista a voltear y devuelve los pancakes volteados  
&emsp; desde esa posición.

 ### &emsp;**'busqProfundidad(self, nodo, ant)'**
 &emsp; Esta funcion recibe como parametros el nodo a partir del cual se realizará la busqueda en profundidad y el movimiento anterior  
 &emsp; que se realizó (en forma de lista) y va a retornar la serie de movimientos que se tiene que realizar para ordenar de menor a mayor los  
 &emsp; pancakes.
 
 ## Como utilizar el código
 &emsp; Para poder utilizar el código se tiene que crear una instancia de la clase "Pancakes" añadiendole como parametro una lista desordenada  
 &emsp; de letras minusculas y luego llamar a la funcion busqProfundidad() dandole como parametro la lista a ordenar y una lista con un solo  
 &emsp; elemento (este elemento no saldrá en el resultado retornado). El resultado de la ejecución será una serie de numeros que indican los  
 &emsp; movimientos que se tienen que realizar para resolver ese problema en caso de que encuentre una solución dentro del limite de profundidad 
 &emsp; o returnará None en caso de no encontrar solución dentro ese limite.
 
&emsp; A continuación se presenta un ejemplo de como utilizar el código:

&emsp; ![image](https://user-images.githubusercontent.com/125157604/229007152-0eee6b19-5f7f-4334-a297-b48c5be75417.png)
