# Práctica 3
*ANÁLISIS DE NODOS* 

## *PLANTEAMIENTO DEL PROBLEMA*
Para realizar cualquier tipo de cálculo en un circuito es necesario conocer los voltajes y corrientes en cada uno de los elementos, para esto recurrimos a las Leyes de voltaje de Kirchhoff, que nos brinda diferentes métodos de análisis, entre ellos está el análisis de nodos. Pero, para comprender esto primero tendremos que comprobarlo para conocer que tan eficiente resulta ser dentro de nuestros cálculos requeridos.

## *OBJETIVO:*
Demostrar experimentalmente al análisis de nodos  a través de las leyes de Kirchhoff para comprobar la efectividad de este método.


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


Fig. 1. Corrientes de enetrada y salida en un nodo


Para que pueda se posible todos los nodos deben tener conductancia, este método produce un sistema de ecuaciones que puede resolverse de varias formas , tales como; Matrices,Crammer,Suma y resta, Sustitución, etc..

¿Que es un nodo?

Un nodo es un punto de intersección , conexió o unión de varios elementos que cunfluyen en el mismo lugar.


¿Como se resuelve?

Se sigue los siguientes pasos:


![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Diagrama%204.png)


Fig. 2. Identificación de nodos en un circuito


Paso 1. Identificar los nodos y asignarles tensiones. Seleccionar uno de ellos como nodo de referencia y asignarle tensión cero.


Paso 2. Establecer una corriente por cada elemento del circuito. Polarizar las resistencias según el criterio:


![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Diagrama%203.png)


Fig. 3. Corriente en una resistencia


Paso 3. Aplicar KCL a cada nodo.


Paso 4. Convertir las corrientes en tensión de acuerdo con la ley de Ohm.


Paso 5. Sustituir en 3 y resolver para las tensiones de nodo.


Nota: El análisis por nodos es más conveniente cuando hay fuentes de corriente.


## *PROCEDIMIENTO*
1. Implemente el siguiente circuito que se muestra en la figura:

![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Diagrama1.png)

Fig.4. Circuito para el análisis de nodos

2. Mida cada uno de los voltajes de nodo y anote los resultados en la tabla
 
 
3. Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito
de la figura , obteniendo los valores de los voltajes de nodo. Anote los resultados en
la tabla.


4. Compare los valores de la tabla y realice sus conclusiones.


## *TABULACIÓN DE DATOS*
|NODO| Resultados Analíticos |Resultados Experimentales|
| ------------- | ------------- | ------------- |
| 1  | 2,9538 | 2,82 |
| 2  | 4,515 | 4,80 |


## *ANÁLISIS DE RESULTADOS*
En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ralizará una tabla donde se muestre  el error relativo de cada valor obtenido:
|NODO| Resultados Analíticos |Resultados Experimentales|%Error|
| ------------- | ------------- | ------------- | ------------- |
| 1  | 2,9538 | 2,82 | 4,53% |
| 2  | 4,515| 4,80 | 6.31% |

## *DIAGRAMA*

![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Diagrama%205.png)

Fig.5. Circuito Simulado en DCAClab

![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Circuito_Simulado.jpg)

Fig.6. Circuito Simulado en TinkerCAD

## *ECUACIONES*

Utilizamos principalmente laley de Ohm, conociendo que su fórmula es I=V/R

donde: 

       Intensidad=Amperio (A)

       Voltaje=Voltio (V)

       Resistencia= Ohmio (omega)

Una vez obtenido este modelo matemático podemos afirmar que se cumple la siguiente ley

V1+V2+V3+V4+...Vn=0


Esta ecuación se cumple siempre y cuando sea de solamente una malla, es decir la sumatoria de voltajes dentro de una malla es igual a cero, afirmando eso se cumple otra ley que nos habla sobres las corrientes, donde las sumatoria de corrientes de entrada es igual a la sumatoria de corrientes de salida:

I(salida)=I(entrada)


Adicionalmente , tomar en cuenta que las intensidades la medimos con la diferencia de potencial que en un caso estándar , tendremos:


(Va-Vb)/(Resistencia)=I


I+I1+I2+I3+......In=0

## *EXPLICACIÓN DEL CIRCUITO*



## *CONCLUSIONES*
- El método de análisis de nodos resulta ser muy práctico dentro  de los cálculos de circuitos eléctricos, como se ha podido evidenciar es un herramienta que nos permite aplicar de manera correcta las leyes de Kirchhoff, de modo organizado y con un número muy reducido de ecuaciones.


## *RECOMENDACIONES*
- Es necesario asegurar los valores que asignamos tanto a las fuentes de voltaje como a las resistencias, ya que se suele cometer errores con las unidades de medida, de igual forma que la conexión esté bien hecha para que las mediciones sean lo más exactas posibles.


- LLevar claro el concepto de esta ley de nodos, para realizar de manera correcta la práctica.


- Tomar en cuenta sobre el peligro que puede ocasionar estos voltajes y la mala utilización de las resistencias.
## *CRONOGRAMA*



## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

## *ANEXOS*

![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Circuito_Simulado_Medicion.jpg)

Fig. 7. Medicones de voltaje en el circuito


![alt text](https://github.com/Kevi7k/Practica3/blob/master/Im%C3%A1genes/Resolucion_de_ejercicio.jpg)

Fig. 8. Resolución del ejercicio
