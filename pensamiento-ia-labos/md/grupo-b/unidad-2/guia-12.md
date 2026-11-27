# GUÍA DE LABORATORIO #12

## Tema

## ● **Estructuras Repetitivas en Python usando Google Colab.**

## Competencias

- Comprender la sintaxis y el uso de bucles for y while en Python.

- Aplicar estructuras repetitivas para procesar conjuntos de datos de salud.

- Desarrollar habilidades prácticas en el uso de Google Colab como herramienta de programación.

## Materiales/Herramientas

- Computadora con acceso a internet.

- Cuenta de Google para el uso de Google Colab.

- Acceso a Microsoft Copilot.

## Fundamento teórico

### 1.1. Estructuras Repetitivas en Python

En la programación, las estructuras repetitivas, también conocidas como bucles, son fundamentales para automatizar tareas que requieren la repetición de instrucciones. Estas estructuras permiten realizar múltiples operaciones de forma eficiente sin necesidad de escribir el mismo código repetidamente. En el campo de la salud, donde se manejan grandes volúmenes de datos, como los historiales médicos, análisis clínicos y registros de pacientes, los bucles son herramientas esenciales para analizar y procesar información rápidamente.

#### 1.1.1. Bucle “WHILE”

Es una estructura de control que ejecuta un bloque de código repetidamente mientras se cumpla una condición especificada. A diferencia del bucle for, que itera sobre una secuencia, el bucle while continúa ejecutándose mientras la condición sea verdadera.

La sintaxis básica es:

## Ejemplo:

El siguiente programa nos muestra una lista de 5 números

## Explicación:

- contador es una variable que empieza con el valor 1.

- La condición contador <= 5 se evalúa antes de cada iteración.

- Si la condición es verdadera, se ejecuta el bloque de código dentro del while.

- Después de ejecutar el bloque de código, contador se incrementa en 1.

- El bucle se repite hasta que contador es mayor que 5.

## ACTIVIDAD 2: Manejo del bucle “WHILE”

Desarrolla un programa que pida al usuario que ingrese un número positivo. El programa debe seguir pidiendo el número hasta que el usuario ingrese un número mayor que cero.

#### 1.1.2. Bucle “FOR”

Es una estructura de control que permite iterar sobre una secuencia (como una lista, tupla, cadena, etc.) o cualquier objeto iterable. Con él, puedes ejecutar un bloque de código repetidamente, una vez por cada elemento de la secuencia.

La sintaxis básica es:

## Ejemplo:

El siguiente programa nos muestra una lista de 5 números

## Explicación:

- numeros, es la secuencia de una lista

- numero es la variable que toma cada valor de la secuencia en cada iteración.

- En cada iteración del bucle, el valor de numero es impreso.

## ACTIVIDAD 1: Manejo del bucle “FOR”

Se requiere un programa en Python que recorra una lista de pacientes y muestre un mensaje indicando que se ha registrado la temperatura de cada uno. Los nombres de los pacientes son: Ana, Luis, Carla, y Pedro.

#### 1.1.3. Uso de la función range() en un Bucle for

Se usa para generar una secuencia de números, que es útil para iterar en un bucle for. La función range() puede tomar uno, dos o tres argumentos:

- range(stop): Genera números desde 0 hasta stop - 1.

- range(start, stop): Genera números desde start hasta stop - 1.

- range(start, stop, step): Genera números desde start hasta stop - 1, incrementando en step.

## Actividad 3: Manejo del bucle “RANGE()”

Imprime un mensaje para cada uno de los 5 días en los que se toman las mediciones de glucosa.

#### 1.1.4. Anidación de bucles

Significa colocar un bucle dentro de otro. Esto es útil para iterar sobre estructuras de datos más complejas, como matrices o listas de listas, donde necesitas realizar operaciones en dos o más niveles de datos.

## Ejemplo:

El siguiente programa imprime una tabla de multiplicar del 1 al 3.

## Explicación:

- ✓ Primer Bucle (for i in range(1, 4)):

   - ✓ Itera sobre los valores del 1 al 3.

- ✓ Segundo Bucle (for j in range(1, 4)):

   - ✓ Por cada valor de i, itera sobre los valores del 1 al 3.

- ✓ print(f"{i} x {j} = {i * j}", end="\t"):

   - ✓ Imprime el resultado de la multiplicación en la misma línea, separado por tabulaciones.

- ✓ print():

   - ✓ Al finalizar el segundo bucle, realiza un salto de línea para comenzar la siguiente fila de la tabla.

#### 1.1.5. Control de bucles: break y continue

##### 1.1.5.1. Break

La instrucción break se usa para salir inmediatamente de un bucle, independientemente de la condición de terminación. Una vez que se ejecuta break, el bucle se detiene y el control del programa pasa a la siguiente línea de código después del bucle.

## Ejemplo:

El siguiente programa imprime números del 1 al 10, pero detente si el número es mayor que 5.

## Explicación:

- El bucle for itera sobre los números del 1 al 10.

- Si el número i es mayor que 5, se ejecuta break y se sale del bucle.

- Solo se imprimen los números del 1 al 5.

##### 1.1.5.2. Continue

La instrucción continue se usa para omitir el resto del código en la iteración actual del bucle y pasar directamente a la siguiente iteración. Esto permite saltar parte del código en el bucle sin detenerlo por completo.

## Ejemplo:

El siguiente programa imprime números del 1 al 10, pero omite los números pares.

## Explicación:

- El bucle for itera sobre los números del 1 al 10.

- Si el número i es par (i % 2 == 0), se ejecuta continue y se omite la impresión de ese número.

- Solo se imprimen los números impares.

Ahora realizaremos un uso combinado de ambos bucles de control con el siguiente ejercicio:

El siguiente programa imprime los números del 1 al 10, pero si encuentras un número mayor que 7, detente; si el número es 5, omítelo.

## Explicación:

- Si i es mayor que 7, se ejecuta break y se sale del bucle.

- Si i es igual a 5, se ejecuta continue y se omite la impresión de ese número.

- Los números del 1 al 7, excepto el 5, se imprimen hasta que el bucle se interrumpe al encontrar un número mayor que 7.

### 2.1. Actividad 4 (Propuesta): Monitorización de Presión Arterial

**Enunciado:** Pide al usuario que ingrese la presión arterial durante 5 días y muestra un mensaje si la presión es demasiado alta (mayor a 140). Termina la solicitud si la presión supera el límite en algún día.

### 2.2. Actividad 5 (Propuesta): Ingreso de Niveles de Glucosa

**Enunciado:** Solicita al usuario que ingrese los niveles de glucosa para 5 días y luego muestra estos datos

## Evaluación:

|**Criterio**|**Puntaje máximo**|**Puntajeobtenido**|
|---|---|---|
|Actividad 1|04 puntos||
|Actividad 2|04 puntos||
|Actividad 3|04 puntos||
|Actividad 4|04 puntos||
|Actividad 5|04 puntos||
|**Total**|**20puntos**||

## Bibliografía:

- Python Software Foundation. (n.d.). Tutorial de control de flujo. En Documentación de Python. Recuperado de <u>https://docs.python.org/3/tutorial/controlflow.html</u>

- Matthes, E. (2020). Python Crash Course: Una introducción práctica y basada en proyectos a la programación. No Starch Press.
