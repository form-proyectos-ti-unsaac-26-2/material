# GUÍA DE LABORATORIO # 12

## Tema

## ● **Estructuras repetitivas**

## Competencias

- Conoce y aplica las estructuras repetitivas

- Desarrollo y aplica las estructuras repetitivas en casos prácticos

- Analiza y desarrolla estructuras repetitivas

## Materiales/Herramientas

- PSEInt

## Fundamento teórico

### 1.1. Introducción a las Estructuras Repetitivas

Las estructuras repetitivas, también conocidas como bucles o ciclos, son fundamentales en la programación, permitiendo ejecutar repetidamente un bloque de código mientras se cumpla una condición. Esto es crucial para automatizar tareas repetitivas y gestionar flujos de control complejos en un programa.

### Importancia de las Estructuras Repetitivas:

- **Eficiencia** : Reducen la necesidad de escribir código repetitivo, facilitando la lectura y mantenimiento del código.

- **Automatización** : Permiten automatizar tareas que requieren la misma acción en múltiples elementos o durante un período de tiempo.

- **Control Dinámico** : Facilitan el manejo de operaciones dependientes de condiciones cambiantes o de la entrada del usuario.

### 1.2. Conceptos y Definiciones

- **Condición de Continuación** : Expresión lógica que se evalúa antes de cada iteración en bucles como Mientras o después de la iteración en bucles como Repetir Hasta. La condición determina si el bucle debe continuar ejecutándose.

- **Variable de Control** : Una variable utilizada para controlar el número de veces que se ejecuta un bucle. Es común en estructuras como Para, donde la variable de control se incrementa o decrementa en cada iteración.

- **Iteración** : Una ejecución completa del bloque de código dentro de un bucle.

- **Bucles Infinitos** : Ocurren cuando la condición de terminación nunca se cumple, provocando que el bucle se ejecute indefinidamente.

### 1.3. Tipos de Estructuras Repetitivas en PSeInt

#### 1.3.1. Mientras (While)

El bucle Mientras es una estructura de control que repite un bloque de código mientras una condición específica sea verdadera. Es ideal para situaciones donde el número de iteraciones no es conocido de antemano y depende de una condición que podría cambiar durante la ejecución.

- **Ventajas** :

   - Flexible en cuanto a las condiciones de finalización.

   - Útil para situaciones donde no se conoce de antemano cuántas veces se ejecutará el bucle.

- **Desventajas** :

   - Potencial para crear bucles infinitos si la condición nunca se vuelve falsa.

   - Requiere una condición bien definida para asegurar que el bucle se detenga en algún momento.

### **Sintaxis en PSeInt** :

#### 1.3.2. Repetir Hasta (Repeat Until)

El bucle Repetir Hasta es similar al Mientras, pero garantiza que el bloque de código se ejecuta al menos una vez, ya que la condición de salida se evalúa después de cada iteración.

- **Ventajas** :

   - Garantiza que el bloque de código se ejecute al menos una vez.

   - Útil cuando el bloque de código debe ejecutarse antes de comprobar la condición.

- **Desventajas** :

`o` Podría ejecutarse más veces de lo necesario si la condición de finalización no está bien definida.

#### 1.3.3. Para (For)

El bucle Para es una estructura repetitiva controlada por contador. Se utiliza cuando se sabe de antemano cuántas veces se ejecutará el bloque de código. Es ideal para situaciones en las que el número de iteraciones es conocido y fijo.

- **Ventajas** :

   - Simple y directo para ciclos con un número de iteraciones conocido.

   - Fácil de leer y entender, especialmente para bucles que requieren contar.

- **Desventajas** :

   - Menos flexible que Mientras y Repetir Hasta para condiciones dinámicas.

**Sintaxis en PSeInt** :

## Aplicación de la guía

### 2.1. Actividad 1: Cálculo del Factorial de un Número

Utilizando la estructura **Mientras** , escribe un programa que calcule la factorial de un número ingresado por el usuario.

Descripción:

El factorial de un número n, representado como n!, es el producto de todos los números enteros positivos desde 1 hasta n. Por ejemplo, 5!=5×4×3×2×1=1205! = 5

## Actividad 2: Suma de Números Positivos

Usando la estructura **Mientras** , escribe un programa que permita al usuario introducir números positivos y sume todos esos números. El programa se detiene cuando el usuario introduce un número negativo.

## Actividad 3: Tabla de Multiplicar

Utilizando la estructura **Para** , escribe un programa que pida al usuario un número y muestre la tabla de multiplicar de ese número desde 1 hasta 10.

## Actividad 4: Promedio de Calificaciones

Desarrolla un programa que permita ingresar las calificaciones de un número indeterminado de estudiantes. El programa deberá calcular y mostrar el promedio de las calificaciones. El ingreso de datos se detiene cuando se introduce una calificación negativa.

## Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|03 puntos||
|Actividad 2|03 puntos||
|Actividad 3|07 puntos||
|Actividad 4|07 puntos||
|**Total**|**20puntos**||

## Bibliografía

- Pineda, J. A. (2021). _Introducción a la programación con PSeInt y Java: Fundamentos, algoritmos y estructuras de datos_ . Editorial ECOE Ediciones.

- Rob, P., & Coronel, C. (2021). _Database Systems: Design, Implementation, & Management_ (13.ª ed.). Cengage Learning.

- Sebesta, R. W. (2020). _Concepts of Programming Languages_ (12.ª ed.). Pearson Education.

- Villalobos, J. (2023). _PSeInt: Herramienta para el aprendizaje de la programación_ PSeInt.
