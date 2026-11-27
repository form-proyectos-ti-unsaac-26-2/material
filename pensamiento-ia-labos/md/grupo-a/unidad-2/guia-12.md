# GUÍA DE LABORATORIO # 12

## Tema

## ● **Algoritmos de Estructura Repetitiva**

## Competencias

Al finalizar la práctica, el estudiante será capaz de:

- Comprender los conceptos básicos de las estructuras repetitivas.

- Identificar y utilizar las diferentes estructuras repetitivas en algoritmos.

- Identificar y utilizar variables como contadores y acumuladores.

- Aplicar estructuras repetitivas en problemas prácticos.

## Materiales/Herramientas

- Python (Editor de código o Google Colab)

## Fundamento teórico

### 1.1. Concepto de Estructuras Repetitivas

Las estructuras repetitivas son herramientas clave en programación, ya que permiten ejecutar un conjunto de instrucciones de manera repetida mientras se cumpla una condición.

- 1) **Inicialización:** Se refiere a la preparación de variables antes de que comience el bucle. Es importante definir adecuadamente las variables que intervienen en la iteración.

- 2) **Condición:** Es la condición que se evalúa en cada iteración. Cuando esta condición se vuelve falsa, el bucle se detiene.

- 3) **Bloque de sentencias:** Son las acciones que se repiten en cada iteración del bucle.

- 4) **Actualización:** Se refiere al cambio o modificación de las variables de control del bucle en cada iteración.

### 1.2. Tipos de Estructuras Repetitivas

### 2.1. Bucle While

Este bucle también se utiliza cuando no se conoce el número exacto de iteraciones y depende de una condición.

Se repite mientras una condición sea verdadera.

- 1) **Inicialización:** Se define antes del bucle.

- 2) **Condición:** Se evalúa al inicio de cada iteración.

- 3) **Bloque de sentencias:** Se ejecuta siempre y cuando la condición sea verdadera caso contrario termina al bucle.

- 4) **Actualización:** Debe modificarse dentro del bucle para evitar bucles infinitos.

### 2.1. Bucle For

Este bucle también se utiliza cuando no se conoce el número exacto de iteraciones y depende de una condición.

Repite un número definido de veces o recorre una secuencia.

- 1) **Inicialización:** Automática al definir el rango.

- 2) **Condición:** Está implícito en el rango o la secuencia.

- 3) **Bloque de sentencias:** Se entra siempre y cuando la condición sea verdadera.

- 4) **Actualización** : Automática al avanzar en la secuencia, es decir cuando se hay ejecutado el bloque de sentencias.

### 2.3. Comparación entre While y For

|**Criterio**|**While**|**For**|
|---|---|---|
|**Uso**|Se utiliza cuando no se conoce de antemano el número de iteraciones necesarias.|Se utiliza cuando se conoce el número exacto de iteraciones o se trabaja sobre una secuencia.|
|**Estructura**|Ejecuta el bloque mientras una condición sea verdadera.|Itera sobre una secuencia de valores o un rango definido.|
|**Condición**|Evaluada al inicio de cada iteración. Si es falsa, el bucle se detiene.|La secuencia (rango) define el número de iteraciones.|
|**Pseudocódigo**|`Mientras (condición):` `//   Instrucciones`|`Para i desde 0 hasta n-1 hacer:` `// Instrucciones`|
|**Código en Python**|`while condición:` `#Instrucciones`|`for i in range(0, n):` `#Instrucciones`|
|**Ejemplo 1:** Imprimir los números de 1 al 5|`contador = 1` `while contador <= 5:` `print(contador)` `contador += 1`|`for i in range(1, 6)` `print(i)`|
|**Explicación delEjemplo 1:**|Se inicializa un contador en 1. El bucle se ejecuta mientras la condición `contador <= 5`sea verdadera. En cada iteración, se imprime el valor del contador y se incrementa en 1. El bucle se detiene cuando`contador`es mayor a 5.|El bucle recorre la secuencia de números generada por`range(1, 6)` (que incluye los números del 1 al 5). En cada iteración, se imprime el valor actual de `i`. El bucle finaliza automáticamente cuando se recorre todo el rango.|
|**Ejemplo 2:** Imprimir los números de 5 al 10|`Realizarlo en clases con ayuda` `del docente`|`for i in range(5, 11):` `print(i)`|
|**Ejemplo 3:** Imprimir los números de 10 al 1|`for i in range(10, 0, -1):` `print(i)`|`Realizarlo en clases con ayuda` `del docente`|
|**Ejemplo 3:** Imprimir los números de 0 al 10 con incrementos de 2 en 2|`Realizarlo en clases con ayuda` `del docente`|`Realizarlo en clases con ayuda` `del docente`|
|**Ejemplo 4:** Registrar un numero entero validando que sea positivo|`Realizarlo en clases con ayuda` `del docente`|`Realizarlo en clases con ayuda` `del docente`|

## Aplicación de la guía

- 2.1. **Actividad 1: Dado un número entero, escribir un programa que determine el número de dígitos**

Inicialmente se puede plantear el siguiente algoritmo:

Pero sin embargo para poder aplicar una estructura repetitiva debemos identificar el bucle (el bloque de sentencias que se va a repetir), entonces para ello planteamos el siguiente esquema

Identificando las 4 partes de una estructura repetitiva tenemos lo siguiente:

**Sección de evaluación (Actividad 1):** En el ejercicio anterior, escribimos un código para contar la cantidad de dígitos impares de un número de tres dígitos utilizando un bucle **while** . Ahora, tu tarea es reescribir ese mismo código utilizando un bucle **for** y además generalizarlo para que funcione con cualquier número de n dígitos.

**2.2. Actividad 2: En uno de los laboratorios de la Carrera de Ingeniería Informática se tiene N estudiantes de la asignatura de PENSAMIENTO COMPUTACIONAL y M estudiantes de la asignatura de TECNOLOGIAS DE LA INFORMACION, para cada estudiante se tiene el promedio final. Escribir un programa que calcule el promedio del laboratorio (ambos cursos).**

- Entrada de datos: El programa primero solicita al usuario el número de estudiantes en PENSAMIENTO COMPUTACIONAL (N) y TECNOLOGÍAS DE LA INFORMACIÓN (M). Luego, pide ingresar los promedios de cada estudiante de ambos cursos.

- Cálculo de sumas: Utiliza un bucle for para iterar sobre cada curso, sumar los promedios de los estudiantes de cada asignatura.

- Cálculo del promedio global: El promedio del laboratorio se obtiene dividiendo la suma total de los promedios entre el número total de estudiantes de ambos cursos.

- Salida: El programa imprime el promedio del laboratorio.

**Sección de evaluación (Actividad 2 ):** En la actividad anterior, el ejercicio se realizó utilizando el bucle **for** . Ahora, tu tarea es reescribir ese mismo código utilizando el bucle **while** . Además, debes incluir validaciones para asegurarte de que el número de estudiantes de ambos cursos y las calificaciones ingresadas sean correctos.

- **2.3. Actividad 3: En el curso de Pensamiento Computacional, se decidió cobrar una cuota de M soles a N compañeros para celebrar el fin de semestre. El docente, para premiar a los alumnos aprobados, decidió aplicar un descuento en la cuota:**

   - Un 50% de descuento para los alumnos con nota 20.

   - Un 30% de descuento para los alumnos con nota mayor a 17.

   - Implementa un programa en Python que permita al delegado cobrar a sus compañeros, aplicar los descuentos correspondientes y calcular el monto total recaudado.

   - Validar las notas y el monto .

## Ejercicios adicionales (Opcional)

- Escribe un programa que solicite al usuario ingresar un número entero n y dibuje un triángulo de asteriscos de altura n.

- Escribe un programa que solicite una palabra o frase y cuente cuántas vocales (a, e, i, o, u) contiene. El programa debe mostrar el número total de vocales.

- Escribe un programa que solicite al usuario ingresar un número entero positivo y sume por separado los números pares e impares desde 1 hasta ese número. El programa debe mostrar ambas sumas por separado.

- Escribe un programa que imprima los primeros n términos de la serie de Fibonacci. La serie comienza con 0 y 1, y cada término subsiguiente es la suma de los dos anteriores.

## Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|05 puntos||
|Actividad 2|05 puntos||
|Actividad 3|10 puntos||
|**Total**|**20puntos**||

## Bibliografía

- Downey, A. (2015). _Think Python: How to Think Like a Computer Scientist_ . O’Reilly Media.

- Zelle, J. (2017). _Python Programming: An Introduction to Computer Science_ . Franklin, Beedle & Associates Inc.
