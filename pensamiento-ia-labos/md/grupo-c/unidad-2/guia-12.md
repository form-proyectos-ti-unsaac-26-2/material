# GUÍA DE LABORATORIO # 12

# Tema

# ● **Algoritmos de Estructura Repetitiva**

# Competencias

Al finalizar la práctica, el estudiante será capaz de:

- Comprender los conceptos básicos de las estructuras repetitivas.

- Identificar y utilizar las diferentes estructuras repetitivas en algoritmos.

- Identificar y utilizar variables como contadores y acumuladores.

- Aplicar estructuras repetitivas en problemas prácticos.

# Materiales/Herramientas

- PSeint

# Fundamento teórico

### 1.1. Concepto de Estructuras Repetitivas

Las estructuras repetitivas son herramientas clave en programación, ya que permiten ejecutar un conjunto de instrucciones de manera repetida mientras se cumpla una condición.

- 1) **Inicialización:** Se refiere a la preparación de variables antes de que comience el bucle. Es importante definir adecuadamente las variables que intervienen en la iteración.

- 2) **Condición:** Es la condición que se evalúa en cada iteración. Cuando esta condición se vuelve falsa, el bucle se detiene.

- 3) **Bloque de sentencias:** Son las acciones que se repiten en cada iteración del bucle.

- 4) **Actualización:** Se refiere al cambio o modificación de las variables de control del bucle en cada iteración.

### 1.2. Tipos de Estructuras Repetitivas

En PSeInt al igual que en otros lenguajes de programación, se tiene dos instrucciones: La instrucción **mientras** y la instrucción **para** , las cuales serán objeto de estudio.

### 2.1. BUCLE MIENTRAS

Este bucle también se utiliza cuando no se conoce el número exacto de iteraciones y depende de una condición.

Se repite mientras una condición sea verdadera.

- 1) **Inicialización:** Se define antes del bucle.

- 2) **Condición:** Se evalúa al inicio de cada iteración.

- 3) **Bloque de sentencias:** Se ejecuta siempre y cuando la condición sea verdadera caso contrario termina al bucle.

- 4) **Actualización:** Debe modificarse dentro del bucle para evitar bucles infinitos.

Ejemplo : Imprimir los numero naturales del 1 al 5

- Inicialización: i = 1

- Condición: (i <= 5)

- Bloque de sentencias: Escribir "Valor de i: ", i

- Actualización: i = i + 1

### 2.1. Bucle For

Este bucle también se utiliza cuando no se conoce el número exacto de iteraciones y depende de una condición.

Repite un número definido de veces o recorre una secuencia.

- 1) **Inicialización:** Automática al definir el rango.

- 2) **Condición:** Está implícito en el rango o la secuencia.

- 3) **Bloque de sentencias:** Se entra siempre y cuando la condición sea verdadera.

- 4) **Actualización** : Automática al avanzar en la secuencia, es decir cuando se hay ejecutado el bloque de sentencias.

Para nuestro ejemplo tenemos:

- Inicialización: i <- 1

- Condición: Hasta 5

- Bloque de sentencias: Escribir "Valor de i: ", i

- Actualización: Paso 1

### 2.3. Comparación entre Mientras y Para

|**Criterio**|**Mientras**|**Para**|
|---|---|---|
|**Uso**|Se utiliza cuando no se conoce de antemano el número de iteraciones necesarias.|Se utiliza cuando se conoce el número exacto de iteraciones o se trabaja sobre una secuencia.|
|**Estructura**|Ejecuta el bloque mientras una condición sea verdadera.|Itera sobre una secuencia de valores o un rango definido.|
|**Condición**|Evaluada al inicio de cada iteración. Si es falsa, el bucle se detiene.|La secuencia (rango) define el número de iteraciones.|
|**PSeint**|**Mientras que (condición)// Bloque de sentenciasFinMientras**|**Para variable <- valor_inicial Hastavalor_final Con Paso incremento// Bloque de sentenciasFinPara**|
|**Ejemplo 1:** Imprimir los números de 1 al 5|**i = 1  // InicializaciónMientras que (i <= 5)  // Condición// Bloque de sentenciasEscribir "Valor de i: ", ii = i + 1  // ActualizaciónFinMientras**|**Para i <- 1 Hasta 5 Con Paso 1  //Inicialización y Condición implícitasEscribir "Valor de i: ", i  // Bloque desentencias// Actualización implícita en laestructura ParaFinPara**|
|**ExplicacióndelEjemplo 1:**|Inicialización: i = 1 Se define antes del bucle para establecer el valor inicial de la variable que se utilizará en la condición del bucle. Condición: i <= 5 Se evalúa al inicio de cada iteración. El ciclo se ejecuta mientras esta condición sea verdadera. Bloque de sentencias: Escribir "Valor de i: ", i Son las acciones que se ejecutan en cada iteración del bucle. Actualización: i = i + 1 Se debe modificar dentro del bucle para evitar bucles infinitos, asegurando que eventualmente la condición se vuelva falsa.|Inicialización: i =1 Se define el valor inicial de la variable i, que comienza en 1. Condición: Hasta 5 El ciclo se repite mientras i sea menor o igual a 5. La condición está implícita en la estructura Para. Bloque de sentencias: Escribir "Valor de i: ", i Son las acciones que se ejecutan en cada iteración del bucle, en este caso, imprimir el valor de i. Actualización: Con Paso 1 i se incrementa en 1 en cada iteración. Esto se maneja automáticamente por el ciclo Para.|

|**Ejemplo 2:** Imprimir los números de 5 al 10|Realizarlo en clases con ayuda del docente|Para i <- 5 Hasta 10 Con Paso 1 // Inicialización en 5, condición hasta 10, incremento de 1 Escribir "Valor de i: ", i  // Bloque de sentencias FinPara|
|---|---|---|
|**Ejemplo 3:** Imprimir los números de 10 al 1|i = 10  // Inicialización Mientras que (i >= 1)  // Condición // Bloque de sentencias Escribir "Valor de i: ", i i = i - 1  // Actualización FinMientras|Realizarlo en clases con ayuda del docente|
|**Ejemplo 3:** Imprimir los números de 0 al 10 con incrementos de 2 en 2|Realizarlo en clases con ayuda del docente|Realizarlo en clases con ayuda del docente|
|**Ejemplo 4:** Registrar un numero entero validando que sea positivo|Realizarlo en clases con ayuda del docente|Realizarlo en clases con ayuda del docente|

# Aplicación de la guía

- 2.1. **Actividad 1:** Dado un número entero de 3 dígitos, escribir un programa que determine el número de veces que aparece el numero 5

Inicialmente se puede plantear el siguiente algoritmo:

El patrón que podemos identificar aquí es que, para cada dígito del número, debemos verificar si es igual a 5 y luego eliminar ese dígito del número. Al trabajar con un número de tres dígitos, este proceso se repite tres veces.

Identificando las 4 partes de una estructura repetitiva tenemos lo siguiente:

- Inicialización: contar_5 = 0 y el número ingresado por el usuario.

- Condición: Mientras el número sea mayor que 0 (num > 0).

- Bloque de sentencias: Obtenemos el último dígito y verificamos si es igual a 5.

- Actualización: Dividimos el número por 10 para eliminar el último dígito.

**Sección de evaluación (Actividad 1):** En el ejercicio anterior, desarrollamos un programa que contaba cuántas veces aparecía el número 5 en un número de tres dígitos utilizando un bucle mientras. Ahora, tu tarea consiste en reescribir ese código empleando un bucle para y, además, generalizarlo para que funcione con un número de n dígitos, permitiendo contar cualquier dígito especificado por el usuario.

- **2.2. Actividad 2:** En uno de los laboratorios de la Carrera de Ingeniería Informática se tiene N estudiantes de la asignatura de PENSAMIENTO COMPUTACIONAL y M estudiantes de la asignatura de TECNOLOGIAS DE LA INFORMACION, para cada estudiante se tiene el promedio final. Escribir un programa que calcule el promedio del laboratorio (ambos cursos).

   - Entrada de datos: El programa primero solicita al usuario el número de estudiantes en PENSAMIENTO COMPUTACIONAL (N) y TECNOLOGÍAS DE LA INFORMACIÓN (M). Luego, pide ingresar los promedios de cada estudiante de ambos cursos.

   - Cálculo de sumas: Utiliza un bucle for para iterar sobre cada curso, sumar los promedios de los estudiantes de cada asignatura.

   - Cálculo del promedio global: El promedio del laboratorio se obtiene dividiendo la suma total de los promedios entre el número total de estudiantes de ambos cursos.

• Salida: El programa imprime el promedio del laboratorio.

**Sección de evaluación (Actividad 2 ):** En la actividad anterior, el ejercicio se realizó utilizando el bucle **para** . Ahora, tu tarea es reescribir ese mismo código utilizando el bucle **mientras** . Además, debes incluir validaciones para asegurarte de que el número de estudiantes de ambos cursos y las calificaciones ingresadas sean correctos.

- 2.3. **Actividad 3:** En el curso de Pensamiento Computacional, se decidió cobrar una cuota de M soles a N compañeros para celebrar el fin de semestre. El docente, para premiar a los alumnos aprobados, decidió aplicar un descuento en la cuota:

   - Un 50% de descuento para los alumnos con nota 20.

   - Un 30% de descuento para los alumnos con nota mayor a 17.

   - Implementa un programa en Python que permita al delegado cobrar a sus compañeros, aplicar los descuentos correspondientes y calcular el monto total recaudado.

   - Considera validar que las notas y el monto sea un valor valido

# Ejercicios adicionales (Opcional)

- Escribe un programa que solicite al usuario ingresar un número entero n y dibuje un triángulo de asteriscos de altura n.

- Escribe un programa que solicite una palabra o frase y cuente cuántas vocales (a, e, i, o, u) contiene. El programa debe mostrar el número total de vocales.

- Escribe un programa que solicite al usuario ingresar un número entero positivo y sume por separado los números pares e impares desde 1 hasta ese número. El programa debe mostrar ambas sumas por separado.

- Escribe un programa que imprima los primeros n términos de la serie de Fibonacci. La serie comienza con 0 y 1, y cada término subsiguiente es la suma de los dos anteriores.

# Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|05 puntos||
|Actividad 2|05 puntos||
|Actividad 3|10 puntos||
|**Total**|**20puntos**||

# Bibliografía

- Joyanes Aguilar, L. (2005). Fundamentos de Programación: Algoritmos, Estructuras de Datos y Objetos. McGraw-Hill Interamericana.

- Tucker, A., & Noonan, R. (2006). Programming Languages: Principles and Paradigms. McGraw-Hill.

- Cormen, T. H., Leiserson, C. E., Rivest, R. L., & Stein, C. (2009). Introduction to Algorithms (3rd ed.). MIT Press.

- Téllez, S. & Méndez, J. (2017). PSeInt: Programación en Pseudocódigo para principiantes. Ediciones UPC.
