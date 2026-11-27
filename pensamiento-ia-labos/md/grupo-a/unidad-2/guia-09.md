# GUÍA DE LABORATORIO #09

## Tema

- **Pensamiento Computacional y estructura secuencial**

## Competencias

- Conoce los conceptos y pilares del pensamiento computacional.

- Conoce y resuelve ejercicios que incluyen estructura secuencial.

- Implementa los ejercicios cuya solución contiene estructura secuencial. utilizando un lenguaje de programación Python.

## Materiales/Herramientas

- Acceso a internet

- Programa Python

- Google Colaboratory

## Fundamento teórico

### 1.1. Pensamiento Computacional

El PC puede entenderse como una forma alternativa de pensamiento relacionada con el surgimiento de las computadoras, dado que genera un ambiente cognitivo donde se juntan el pensamiento ingenieril, el científico y el lógico matemático (Wing, 2008). Esto implica desarrollar un mayor nivel de abstracción con el fin de resolver problemas concretos del mundo real. Se aplica, preferentemente, al diseño de sistemas (a través de operaciones de modelado) y a la solución de problemas por medio de su automatización en computadoras (pensamiento algorítmico y programación). El pensamiento computacional gira en torno a dos dimensiones: como vínculo entre varias formas de pensamiento (ingenieril, científico y lógico -matemático) sobre la base de utilizar mecanismos computacionales y como recurso orientado al fomento de la abstracción y el análisis de problemas. En el año 2010, Wing y otros autores actualizaron y dotaron de una precisión mayor a su definición de PC, al indicar:

_“Pensamiento computacional son los procesos de pensamiento implicados en la formulación de problemas y sus soluciones para que estas últimas estén representadas de forma que puedan llevarse a cabo de manera efectiva por un procesador de información.”_

### 1.2. Estructura secuencial

La estructura secuencial es aquella donde las instrucciones se ejecutan una a continuación de otra en el orden en que estas fueron escritas. En este tipo de estructuras se hacen uso de instrucciones simples, tales como las sentencias de entrada y/o de salida y de las sentencias de asignación.

### 1.3. Operadores de división entera ( Div y Mod)

**Div:** División entera: permite dividir dos números enteros, produciendo también un resultado entero que sería el Cociente de dicha división. La parte decimal no se considera.

**Mod:** Residuo de una división entera.

## Ejemplo:

## Por lo tanto:

**19 div 5 = 3**

**19 mod 5 = 4**

## Otros ejemplos:

|**Expresión**|**Resultado**|
|---|---|
|**123 mod 10=**|**3**|
|**34   div   7 =**|**4**|
|**14 div 5=**|**2**|
|**365 div 10 =**|**36**|

### 1.4. Sentencias básicas en Python

Python es un lenguaje que todo el mundo debería conocer. Su sintaxis simple, clara y sencilla; el tipado dinámico, el gestor de memoria, la gran cantidad de librerías disponibles y la potencia del lenguaje, entre otros, hacen que desarrollar una aplicación en Python sea sencillo, muy rápido y, lo que es más importante, divertido. (Raul, 2011)

|**Operad+**|**ores aritméticos** Suma|
|---|---|
|**-**|Resta|
|**-**|Negación|
|*|Multiplicación|
|**|Exponente|
|**/**|División|
|**//**|División entera (div)|
|**%**|Módulo (mod)|

## Sentencias en python:

||**Sentencias de entrada:**|
|---|---|
|**Léxico**|**input**|
|**Sintaxis**|Variable=input(“texto”)|
|**Semántica**|Nos permite instruir al computador que espera a que el usuario digite un valor y lo almacene en una variable.|
||**Ejemplos:**|
||**ciudad**=input(“Ingrese una ciudad”)→datos de tipo Texto|
||**nroAlumno**= int(input(“ingrese el número de alumnos “))→datos enteros **precioVenta**=float(input(“ingrese el precio de venta “)) -→datos reales|

||**Sentencias de asignación**|
|---|---|
|**Léxico**|**=**|
|**Sintaxis**|Variable= Expresión|
|**Semántica**|Mediante este símbolo (=) se le indica al computador que primero efectúe la expresión matemática y luego el resultado lo asigne a la variable.|
||Ejemplo: Área=3.1416*(radio*radio) Resultado= 2*(3) + 20|
||**Sentencias de salida**|
|**Léxico**|**print**|
|**Sintaxis**|print(variable)|
|**Semántica**|Mediante esta sentencia se indica al computador que muestre los resultados en pantalla. **Ejemplos:** print(variable1, variable2, variable3) print(expresión) print(“texto”, variable)|

## Aplicación de la guía

### 2.1. Actividad 1: Ejercicios de pensamiento computacional:

André necesita llegar a su casa y usa un automóvil autónomo (que está en un estado rudimentario de desarrollo, muy lejos de la inteligencia artificial deseada). El automóvil está programado con solo tres instrucciones:

- ➢ I: gira 90° a la izquierda

- ➢ D: gira 90° a la derecha

- ➢ A: avanza hasta el próximo cruce.

Utilizando las 3 instrucciones, ¿puedes indicar los pasos que guía a André hasta su casa, por el camino más corto (en cantidad de instrucciones)?

**Ejemplo:** nuestro destino será el árbol solitario: como se muestra en la imagen, se debe de seguir el siguiente algoritmo: A-A-A-I-A-A-A y se llega al árbol.

Se podrían seguir otros caminos, pero esta solución responde a la solución con camino más corto, es importante que los algoritmos sean eficientes, así que se utilizan menos recursos.

**Solución:** el camino más corto que André debe seguir seria:

|**Respuesta:**|**A-I-A-A-A-A-I-A-A**|
|---|---|

En el plano hay 2 posibles caminos, pero nos quedaremos con este camino porque es importante que el algoritmo sea eficiente.

### 2.2. Actividad 2: Cual sería el algoritmo

El siguiente laberinto contiene 2 tesoros marcados como X y Y. Los bloques verdes son paredes y los bloques blancos son los caminos por donde puede caminar un robot.

## Las instrucciones que puede seguir el robot son las siguientes:

- ➢ Ax: avanza x bloques

- ➢ D: gira 90° a la derecha

- ➢ I: gira 90° a la izquierda

- ➢ R: Recoge el tesoro.

Inicialmente el robot está en la posición S y está mirando hacia la derecha del mapa. El robot solo puede recoger el tesoro si está en la misma casilla del mapa que el tesoro.

Ejemplo: el siguiente algoritmo muestra como los pasos que debe de seguir el robot para agarrar el tesoro X:

**Respuesta:** A1-D-A3-D-A1-I-A2-I-A2-R

## ¿Cuál sería el algoritmo para que el robot pueda agarrar el tesoro Y?

**Respuesta:**

### 2.3. Actividad 3: Analiza el ejercicio y escribe tu respuesta.

Un ratón de laboratorio está situado en la entrada de un sistema de cañerías y el objetivo es que llegue al queso que se encuentra al final del quinto caño. Estas son las instrucciones que el ratón siempre sigue:

1. Baja por el tubo hasta que aparezca un túnel nuevo.

2. Cada vez que te encuentres con un túnel nuevo debes de atravesarlo

3. Volver a la instrucción 1.

## ¿Por cuál de los tubos debe ingresar el ratón para llegar al queso?

**Respuesta:**

### 2.4. Actividad 4: Codifica los siguientes ejercicios en Python

## a. Ejercicio 1: Calcular el área de un trapecio

## b. Ejercicio 2: Calcular la distancia entre 2 puntos

### 2.5. Actividad 5: Codifica los siguientes ejercicios

## a. Ejercicio 3: Dado un número de 3 cifras, calcular la multiplicación de la unidad y la centena

## b. Ejercicio 4: Dado un numero de 3 cifras, escribir un programa que determine el número de dígitos impares.

### 2.6. Actividad 6 (Propuesta): Implementa el siguiente ejercicio

**Ejercicio 5:** Escribir un algoritmo que evalúe la función: **f(x)= 2x**<sup>**2**</sup> **+ 3x-5.**

**Ejercicio 6:** Dado 3 notas, escribir un programa que determine el promedio de un alumno.

### 2.7. Actividad 7 (Propuesta): Resuelve el ejercicio

**Ejercicio 6:** Una tienda ofrece el 15% a todas sus compras. Escribir un programa que lea la cantidad y el precio unitario. del producto. Calcular el descuento y el precio final a pagar.

### 2.8. Actividad 8 (Propuesta): Resuelve

**Ejercicio 7:** Dado un número de 4 cifras, escribir un programa que determine el número de dígitos pares.

## Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 2|03 puntos||
|Actividad 3|03 puntos||
|Actividad 4|02 puntos||
|Actividad 5|02 puntos||
|Actividad 6|04 puntos||
|Actividad 7|03 puntos||
|Actividad 8|03 puntos||
|**Total**|**20puntos**||

## Bibliografía

- <mark>López García, J. C. (2009). Algoritmos y Programación: Guía para docentes.</mark>

- <mark>González Duque, R. (2011). Python para todos.</mark>

   - https://libguides.ulima.edu.pe/Bases_datos_Tutoriales/APA_PsycNET
