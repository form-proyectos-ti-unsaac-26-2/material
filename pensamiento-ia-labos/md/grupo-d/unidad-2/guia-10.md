# GUÍA DE LABORATORIO #10

## Tema

## ● **Estructura selectiva simples y dobles**

## Competencias

- Conoce las estructuras selectivas simples y estructuras selectivas dobles

- Resuelve ejercicios que incluyen estructuras selectivas simples y estructuras selectivas dobles

- Implementa los ejercicios cuya solución contiene estructuras selectivas simples y estructuras selectivas dobles utilizando un lenguaje de programación – (PSeInt )

## Materiales/Herramientas

● Programa Pseint Descarga del programa Pseint: <u>https://pseint.sourceforge.net/index.php?page=descargas.php&os=w32</u>

- <mark>Link del programa:</mark> Link Online (loguearse con su cuenta): <u>https://www.rollapp.com/launch/pseint</u>

## Fundamento teórico

### 1.1. Estructura selectiva simple

### ¿Cómo tomar decisiones en un algoritmo?

Uno de los métodos para el control de la ejecución de los pasos de un algoritmo es la **Toma de Decisiones,** las cuales se construyen por medio de las Estructuras Selectivas.

Una estructura selectiva define un conjunto de alternativas de flujo, de las cuales solo se puede elegir una por medio de la evaluación de una o más condiciones, para continuar con la ejecución del algoritmo. Todas las alternativas finalizan en un paso común, luego del cual, puede continuar de forma secuencial.

### 1.2. Estructura selectiva simple

Es una estructura de control que permite ejecutar un grupo de acciones dependiendo de alguna condición lógica. Las estructuras de control permiten controlar el flujo del programa para determinar cuáles acciones se ejecutan y cuáles no. En este tipo de estructura se ejecutan un conjunto de acciones si y sólo si, se cumple o se hace verdadera la condición.

**Sintaxis**

:

Si **condición** entonces Inicio

{Conjunto de Instrucciones}

fin **Semántica**

FinSi

|**Si**|Indica inicio de instrucción condicional|
|---|---|
|**condición**|Expresión booleana. Sólo puede tomar 2 valores: Verdadero o Falso|
|**entonces**|Indica inicio de sección correspondiente a instrucciones del bloque verdadero|
|**inicio…fin**|Delimitadores de instrucciones, cuando existe más de una instrucción|
|**{Conjunto de**|Bloque de instrucciones   ejecutarse. Puede ser 1 o más instrucciones|
|**instrucciones}**||
|**FinSi**|Indica la finalización de la estructura selectiva|

### Diagrama de flujos

Figura 1: Representación gráfica de la estructura selectiva Fuente: Introducción a la programación

### 1.3. Estructura selectiva doble

La estructura selectiva doble permite que, si se cumple una condición, se ejecute un conjunto de instrucciones, y si no se cumple, se ejecuten otras instrucciones diferentes.

Esta estructura condicional consta de dos bloques, uno que se ejecuta si la condición es verdadera y otro que se ejecuta si la condición es falsa.

**Sintaxis** :

Si **condición** entonces Inicio {Conjunto deInstrucciones 1} Fin **CasoContrario** Inicio {Conjunto de Instrucciones 2} Fin

FinSi

## Semántica

|**Si**|Indica inicio de instrucción condicional|
|---|---|
|**condición**|Expresión booleana. Sólo puede tomar 2 valores: Verdadero o  Falso|
|**entonces**|Indica inicio de sección correspondiente a instrucciones del bloque**verdadero**|
|**inicio…fin**|Delimitadores de instrucciones, cuando existe más de una instrucción|
|**{Conjunto de**|Bloque de instrucciones a ejecutarse si la condición resulta ser|
|**instrucciones1}**|**Verdadera**. Puede ser 1 o más instrucciones|
|**CasoContrario**|Indica inicio de sección correspondiente a instrucciones del bloque**Falso**|
|**{Conjunto deinstrucciones2}**|Bloque de instrucciones a ejecutarse si la condición resulta ser **Falso**. Puede ser 1 o más instrucciones|
|**FinSi**|Indica la finalización de la estructura selectiva|

Figura 2: Representación gráfica de la estructura selectiva

Fuente: Introducción a la programación

## Aplicación de la guía

- **●.1. Actividad 1: Implemente en PSeInt el siguiente ejercicio (Estructura selectiva simple)**

Dado la edad de una persona, determinar si es mayor de edad (mayor de edad cuando la edad es Mayor o igual a 18 años)

- **●.2. Actividad 2: Implemente en PSeInt el siguiente ejercicio (Estructura selectiva simple)**

Dado un número, determinar si el número es múltiplo de 4.

- **●.3. Actividad 3 (Propuesta): Implemente en PSeInt el siguiente ejercicio (Estructura selectiva doble)**

Escribir un algoritmo que lea 2 números y determine cuál es el mayor.

## ● **Actividad 4 (Propuesta): Implemente en PSeInt el siguiente ejercicio (Estructura selectiva doble)**

Escribir un algoritmo que determine si una persona es mayor o menor de edad.

- **●.1. Actividad 5 (Ejercicios Propuestos): Formar grupos de 4 alumnos y asignar 3 ejercicios diferentes a cada grupo.**

   - Dado un ángulo determinar si el Ángulo es recto

   - Dado un número determinar si el número es positivo o negativo

   - Dado un número de 2 dígitos calcular si la suma de sus dígitos es mayor que 5

   - Dado un número de 2 dígitos calcular si el producto de sus dígitos es un número par

   - Dado un número de 3 cifras, determinar si la suma de sus dígitos es múltiplo de 5

   - Dado el largo y ancho de una habitación, calcular el área de dicha habitación, considerar que el ancho y largo deben ser mayores a 0.

   - Escribir un programa que determine el menor de 3 números

   - A un trabajador le pagan según sus horas trabajadas por una tarifa de pago por hora (20 soles por hora). Si la cantidad de horas trabajadas es mayor a 40 horas. la tarifa se incrementa en un 50% para las horas extras. Calcular

el salario del trabajador dadas las horas trabajadas.

- Dada la temperatura del dia, determinar si el día será caluroso o no (se considera día caluroso si la temperatura es mayor a 20 grados).

- <mark>E</mark> n una llantería se ha establecido una promoción de las llantas según lo siguiente: Si se compran menos de cinco llantas el precio es de 300 soles cada una, y si se compra más de 5 llantas el precio por llanta es de 200 soles <mark>. Calcular el monto final a pagar.</mark>

## Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|02 puntos||
|Actividad 2|02 puntos||
|Actividad 3|03 puntos||
|Actividad 4|03 puntos||
|Actividad 5|10 puntos||
|**Total**|**20puntos**||

## Bibliografía

- <mark>López García, J. C. (2009). Algoritmos y Programación: Guía para docentes.</mark>

- <mark>Bustamante, O. A., & Ramos, J. V. M. (2007). Introducción a la programación.</mark> _<mark>Cd. de México: Universidad Autonoma de México</mark>_ <mark>.</mark>
