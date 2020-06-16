# Práctica 3
*ANÁLISIS DE NODOS* 

## *PLANTEAMIENTO DEL PROBLEMA*
Para realizar cualquier tipo de cálculo en un circuito es necesario conocer los voltajes y corrientes en cada uno de los elementos, para esto recurrimos a las Leyes de voltaje de Kirchhoff, que nos brinda diferentes métodos de análisis, entre ellos está el análisis de nodos. Pero, para comprender esto primero tendremos que comprobarlo para conocer que tan eficiente resulta ser dentro de nuestros cálculos requeridos.

## *OBJETIVO:*
Comprobar de manera empírica el análisis de nodos.


## *LISTA DE MATERIALES:*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Fuente de voltaje de C.D |
| 1  | Multímetros digitales |
|  1 | Resistor de 1,8k  |
|  1 | Resistores de 470  |
| 1 | Resistor de 1,5k  |
| 1  | Resistor de 3,9k  |
|  1  | Resistor    2,2k  |
| 1  | Protoboard      |

## *MARCO TEÓRICO*
Para realizar el análisis de cicrcutos, exsiten varios metodos para poder resolverlos, entre ellos estan el metodo de las mallas, el de las corrientes y el de los nodos.Que en este tema especificaremos sobre el metodo de los nodos que no es nada menos que determinar la tensión (Su diferencia de potencial) de uno o más nodos.

En esta forma de resolver teoricamente un circuito , nos dice que para todo nodo se escribe una ecuación , con la única condición de que la suma de esas corrientes sea igual a cero en cualquier instante, por lo que una carga nunca puede acumularse en un nodo.

Estas corrientes se las escribe en funcion del voltaje , utilizando una vez mas la ley de Omh.

Donde se cumple que la sumatoria de todas las corrientes que entran en un nodo son igual a las que salen.


![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Diagrama%202.png)


Figura 1.


Para que pueda se posible todos los nodos deben tener conductancia, este método produce un sistema de ecuaciones que puede resolverse de varias formas , tales como; Matrices,Crammer,Suma y resta, Sustitución, etc..

¿Que es un nodo?

Un nodo es un punto de intersección , conexió o unión de varios elementos que cunfluyen en el mismo lugar.


¿Como se resuelve?

Se sigue los siguientes pasos:


![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Diagrama%204.png)


Figura 2.


Paso 1. Identificar los nodos y asignarles tensiones. Seleccionar uno de ellos como nodo de referencia y asignarle tensión cero.


Paso 2. Establecer una corriente por cada elemento del circuito. Polarizar las resistencias según el criterio:


![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Diagrama%203.png)


Figura 3


Paso 3. Aplicar KCL a cada nodo.


Paso 4. Convertir las corrientes en tensión de acuerdo con la ley de Ohm.


Paso 5. Sustituir en 3 y resolver para las tensiones de nodo.


Nota: El análisis por nodos es más conveniente cuando hay fuentes de corriente.


## *PROCEDIMIENTO*
Implemente el siguiente circuito que se muestra en la figura:

![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Diagrama1.png)


 .Mida cada uno de los voltajes de nodo y anote los resultados en la tabla
 
 
 Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito
de la figura , obteniendo los valores de los voltajes de nodo. Anote los resultados en
la tabla.


Compare los valores de la tabla y realice sus conclusiones.


## *TABULACIÓN DE DATOS*
|NODO| Resultados Analíticos |Resultados Experimentales|
| ------------- | ------------- | ------------- |
| 1  | 999 | 999 |
| 2  | 999 | 999 |
|  3 | 999  | 999 |
|  4 | 999  | 999 |


## *ANÁLISIS DE RESULTADOS*
En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ralizará una tabla donde se muestre  el error relativo de cada valor obtenido:
|NODO| Resultados Analíticos |Resultados Experimentales|%Error|
| ------------- | ------------- | ------------- | ------------- |
| 1  | 999 | 999 | 999% |
| 2  | 999 | 999 | 999% |
|  3 | 999  | 999 | 999% |
|  4 | 999  | 999 | 999% |

## *DIAGRAMA*


## *ECUACIONES*



## *EXPLICACIÓN DEL CIRCUITO*



## *CONCLUSIONES*
- El método de análisis de nodos resulta ser muy práctico dentro  de los cálculos de circuitos eléctricos, como se ha podido evidenciar es un herramienta que nos permite aplicar de manera correcta las leyes de Kirchhoff, de modo organizado y con un número muy reducido de ecuaciones.


## *RECOMENDACIONES*


## *CRONOGRAMA*



## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

## *ANEXOS*
