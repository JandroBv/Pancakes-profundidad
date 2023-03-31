# Pancakes Profundidad

Este programa resuelve el problema de pancake sorting mediante el uso de DFS (Depth First Search) o busqueda por profundidad.

**Lenguaje utilizado**: Python

## Funciones

 ### **'__ init __(self, pancakes, profundidad)'**
 Este el constructor de la clase Pancakes que recibe como parametros una lista de letras desordenadas y una profundidad limite para el  
 programa.
 ### **'voltear(self, posicion, pancakes)'**
 
Esta funcion recibe como parametro la posición donde se van a voltear los pancakes y la lista a voltear y devuelve los pancakes volteados  
desde esa posición.

 ### **'busqProfundidad(self, nodo, ant)'**
 Esta funcion recibe como parametros el nodo a partir del cual se realizará la busqueda en profundidad y el movimiento anterior  
  que se realizó (en forma de lista) y va a retornar la serie de movimientos que se tiene que realizar para ordenar de menor a mayor los  
 pancakes.
 
 ## Como utilizar el código
 Para poder utilizar el código se tiene que crear una instancia de la clase "Pancakes" añadiendole como parametro una lista desordenada  
 de letras minusculas y luego llamar a la funcion busqProfundidad() dandole como parametro la lista a ordenar y una lista con un solo  
 elemento (este elemento no saldrá en el resultado retornado). El resultado de la ejecución será una serie de numeros que indican los  
 movimientos que se tienen que realizar para resolver ese problema en caso de que encuentre una solución dentro del limite de profundidad 
 o returnará None en caso de no encontrar solución dentro ese limite.
 
A continuación se presenta un ejemplo de como utilizar el código:

![image](https://user-images.githubusercontent.com/125157604/229007152-0eee6b19-5f7f-4334-a297-b48c5be75417.png)
