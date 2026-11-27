# GUÍA DE LABORATORIO 11

### Tema

- **Estructuras selectivas anidadas y múltiples**

### Competencias

- Conoce y aplica razonamiento lógico con condicionales anidadas y múltiples

### Materiales/Herramientas

- PSeInt

### Fundamento teórico

### 1.1. Estructura condicional anidada

El proceso de toma de decisiones suele ocurrir en niveles. Por ejemplo, cuando vas al restaurante y eliges huevos para el desayuno, has tomado una decisión de primer nivel. Ahora el camarero te pregunta qué tipo de tostada quieres con los huevos. El camarero no haría esta pregunta si hubieras pedido panqueques, por lo que la selección de tostadas se convierte en una decisión de segundo nivel. Cuando llega el desayuno, decides si quieres usar mermelada en tu tostada. Esta es una decisión de tercer nivel. Si hubieras seleccionado un tipo de tostada que no combina bien con mermelada, es posible que no hubieras tenido que tomar esta decisión en absoluto. Este proceso de toma de decisiones en niveles, en el que cada nivel depende de la decisión tomada en el nivel anterior, se llama anidamiento. Los desarrolladores a menudo utilizan técnicas de anidamiento para crear aplicaciones que pueden tomar decisiones complejas basadas en diversas entradas. Otro ejemplo seria para determinar si un alumno está APROBADO, DESAPROBADO o REPROBADO según su promedio (Figura 1).

**Figura 1:** Ejemplo estructura condicional anidada **Fuente:** Propia

### 1.2 Estructura selectiva múltiple

Una **estructura selectiva múltiple** es un tipo de estructura de control en programación que permite tomar decisiones entre varias alternativas basadas en el valor de una variable o expresión. A diferencia de una estructura selectiva simple (como `if-else` ), donde se evalúa una condición y se ejecuta un bloque de código si esta es verdadera o falsa, en una **estructura selectiva múltiple** se evalúa una sola expresión o variable contra diferentes valores posibles, ejecutando el bloque de código asociado al valor que coincida (Figura 2).

**Figura 2:** Ejemplo estructura condicional anidada **Fuente:** https://cienciayt.com/programacion/logica-de-programacion/estructura-selectiva-multiple/

Las estructuras selectivas múltiples, también conocidas como **estructuras de decisión múltiple** o **switch-case** en algunos lenguajes de programación, permiten gestionar de forma más clara y eficiente situaciones en las que hay varias alternativas posibles. Cada alternativa está asociada con un valor específico de la expresión que se evalúa.

Cuando la expresión o variable coincide con uno de los valores especificados, se ejecuta el bloque de código correspondiente. Si no hay coincidencia, se puede definir una opción por defecto que se ejecuta en caso de que ninguna condición se cumpla.

**Ejemplo en** PSeInt **:**

**Psint** : Usa la estructura `Segun` para la selección múltiple.

**Segun variable** Hacer

**valor1:** // Código a ejecutar si variable es igual a valor1 **valor2:**

// Código a ejecutar si variable es igual a valor2 **De otro modo:**

// Código a ejecutar si ninguna de las opciones coincide

### FinSegun

## Uso Común

Las estructuras selectivas múltiples se utilizan frecuentemente en:

- **Menús de opciones** : Para manejar múltiples selecciones en sistemas de menú.

- **Procesos de clasificación** : Para clasificar datos en categorías definidas.

- **Conversión de valores** : Como por ejemplo, convertir un valor numérico en texto descriptivo, como días de la semana, meses, calificaciones, etc.

### Aplicación de la guía

### 2.1. Actividad 1: Aplicación de descuentos

Realizar un programa usando PSeInt para una empresa que vende zapatillas donde se ingresa el precio de la zapatilla (en soles), el tipo y la talla. Luego debe mostrar el monto comprado, el importe del descuento y el monto a pagar.

### Tabla de descuentos

|||**Tipos**||
|---|---|---|---|
|**Tallas**|**Running**|**Montain**|**Urban**|
|Hasta 40|5%|10%|15%|
|De 41 hasta 45|2%|5%|12%|
|De 46 a más|1%|2%|5%|

El problema presentado en la imagen solicita que se desarrolle un programa para una tienda que vende zapatillas. El programa debe ingresar el **precio de la zapatilla** , el **tipo** de zapatilla (Running, Montain o Urban) y la **talla** . Luego, se debe calcular y mostrar el monto comprado, el importe del descuento según la tabla de descuentos proporcionada y el monto total a pagar.

A continuación se presenta una explicación paso a paso de cómo sería la solución con estructura selectiva anidada:

### **A. Entrada de datos** :

   - a. Se solicita el **precio** de la zapatilla.

   - b. Se solicita el **tipo** de zapatilla (Running, Montain, Urban).

   - c. Se solicita la **talla** .

- **B. Estructura selectiva anidada** :

   - a. Primero, se evalúa el **tipo** de zapatilla:

      - i. Si el tipo es **Running** , se utiliza otra estructura selectiva anidada para verificar la talla y aplicar el descuento correspondiente.

      - ii. Si el tipo es **Montain** , se realiza la misma evaluación con las tallas.

      - iii. Si el tipo es **Urban** , se sigue la misma lógica con las tallas.

   - b. Dentro de cada caso (tipo de zapatilla), se verifica si la talla es **hasta 40** , **de 41 a 45** , o **46 a más** y se aplica el descuento correspondiente.

- **C. Cálculo del monto** :

   - a. Se calcula el **importe del descuento** multiplicando el precio por el porcentaje de descuento.

   - b. Se calcula el **monto total a pagar** restando el importe del descuento del monto total.

- **D. Salida de datos** :

   - a. Se muestra el monto total de la compra, el descuento aplicado y el monto final a pagar.

## Pseudocódigo (simplificado) usando PSeInt con estructura selectiva anidada:

```
Algoritmo VentaZapatillas_Anidado
    // Declaración de variables
    Definir precio, descuento, montoAPagar Como Real
    Definir talla, tipo Como Entero
    Definir tipoTexto Como Caracter
    // Entrada de datos
    Escribir "Ingrese el precio de la zapatilla (en soles):"
    Leer precio
    Escribir "Ingrese el tipo de zapatilla (1=Running,
2=Montain, 3=Urban):"
    Leer tipo
    Escribir "Ingrese la talla de la zapatilla:"
    Leer talla
    // Inicializar descuento en 0
    descuento = 0
    // Estructura selectiva anidada para determinar el
descuento
    Si tipo = 1 Entonces // Running
        tipoTexto = "Running"
        Si talla <= 40 Entonces
            descuento = 0.05
Sino
Si talla >= 41 y talla <= 45 Entonces
descuento = 0.02
Sino
descuento = 0.01
FinSi
FinSi
Sino
Si tipo = 2 Entonces // Montain
tipoTexto = "Montain"
Si talla <= 40 Entonces
descuento = 0.10
```

```
Sino
Si talla >= 41 y talla <= 45 Entonces
descuento = 0.05
Sino
descuento = 0.02
FinSi
FinSi
Sino
Si tipo = 3 Entonces // Urban
tipoTexto = "Urban"
Si talla <= 40 Entonces
descuento = 0.15
Sino
Si talla >= 41 y talla <= 45 Entonces
descuento = 0.12
Sino
descuento = 0.05
FinSi
FinSi
Sino
Escribir "Tipo no válido"
FinSi
FinSi
FinSi
// Cálculo del descuento y monto a pagar
montoDescuento = precio * descuento
montoAPagar = precio - montoDescuento
// Resultados
Escribir "Tipo de zapatilla seleccionado: ", tipoTexto
Escribir "Monto comprado: S/ ", precio
Escribir "Descuento aplicado: S/ ", montoDescuento
Escribir "Monto a pagar: S/ ", montoAPagar
FinAlgoritmo
```

### 2.2. Actividad 2: (Propuesta): Resuelve el ejercicio

Realizar un programa usando PSeInt que luego de ingresar el sueldo base, categoría, número de hijos y edad de un empleado se obtiene su gratificación, que se aumenta a su sueldo básico y posteriormente se le descuenta un 11% por AFP. Finalmente, mostrar el sueldo inicial, gratificación, descuento y sueldo final. Usar la siguiente tabla

### Tabla de gratificaciones

||**Categoría A**||**Categoría B**||
|---|---|---|---|---|
|**Edad**|**Sin Hijos**|**Con Hijos**|**Sin Hijos**|**Con Hijos**|
|**Hasta 30**|100|120|200|220|
|**De 31 hasta 40**|150|180|250|280|
|**De 41 a más**|200|250|300|350|

### 2.3. Actividad 3: Calculadora

Construir un programa en PSeInt que permita ingresar dos números y un símbolo (+, -, x, /) y dependiendo del operador devuelve la suma, la diferencia, el producto o la división.

Nota: verificar que el divisor no sea cero y mostrar una advertencia si se ingresa un valor diferente a esos símbolos.

## Requerimientos del problema:

### **A. Entrada de datos** :

   - a. Se deben ingresar **dos números** (número1 y número2).

   - b. Se debe ingresar un **símbolo** que puede ser: `+` , `-` , `x` (para la multiplicación) o `/` (para la división).

- **B. Operaciones** :

   - a. Si el símbolo es **'+'** , el programa debe calcular la **suma** de los dos números.

   - b. Si el símbolo es **'-'** , el programa debe calcular la **resta** (diferencia) de los dos números.

   - c. Si el símbolo es **'x'** , el programa debe calcular el **producto** de los dos números.

   - d. Si el símbolo es **'/'** , el programa debe calcular la **división** , pero verificando que el segundo número (divisor) no sea cero.

- **C. Validaciones** :

   - a. Si el **símbolo** ingresado no es válido, es decir, no corresponde a `+` , `-` , `x` o `/` , el programa debe mostrar un mensaje de advertencia indicando que el operador no es reconocido.

   - b. Si el operador es `/` y el **segundo número** es cero, el programa debe mostrar un mensaje de advertencia porque no se puede dividir entre cero.

- **D. Salida de datos** :

   - a. El programa debe mostrar el resultado de la operación o un mensaje de advertencia según las validaciones.

```
Algoritmo OperacionesMatematicas
    // Declarar las variables
    Definir numero1, numero2, resultado Como Real
    Definir operador Como Caracter
    // Solicitar los números
    Escribir "Ingrese el primer número:"
    Leer numero1
    Escribir "Ingrese el segundo número:"
    Leer numero2
    // Solicitar el operador
```

```
    Escribir "Ingrese el operador (+, -, x, /):"
    Leer operador
    // Estructura selectiva múltiple para determinar la
operación
    Segun operador Hacer
Caso "+":
            resultado = numero1 + numero2
            Escribir "La suma es: ", resultado
Caso "-":
            resultado = numero1 - numero2
            Escribir "La resta es: ", resultado
Caso "x":
            resultado = numero1 * numero2
Escribir "El producto es: ", resultado
Caso "/":
            // Verificar si el divisor es 0
            Si numero2 = 0 Entonces
                Escribir "Error: No se puede dividir entre
cero."
            Sino
                resultado = numero1 / numero2
                Escribir "La división es: ", resultado
            FinSi
    FinSegun
FinAlgoritmo
```

## Explicación del pseudocódigo:

- **A. Declaración de variables** : Se declaran tres variables `numero1` , `numero2` y `resultado` de tipo **Real** para almacenar los dos números y el resultado de la operación. La variable `operador` es de tipo **Caracter** y almacenará el símbolo ingresado.

- **B. Lectura de datos** : El programa solicita al usuario los dos números y el símbolo de la operación.

- **C. Estructura`Segun`** :

   - a. La estructura `Segun` evalúa el contenido de la variable `operador` . Dependiendo del símbolo ingresado, realiza una de las operaciones matemáticas (suma, resta, multiplicación o división).

   - b. En el caso de la división ( `/` ), antes de realizar la operación, se verifica si el divisor ( `numero2` ) es cero. Si es así, se muestra un mensaje de error. Si no, se realiza la operación normalmente.

   - c. Si el símbolo ingresado no es uno de los válidos ( `+` , `-` , `x` , `/` ), se muestra un mensaje de advertencia.

- **D. Resultados** : El programa muestra el resultado de la operación correspondiente o un mensaje de advertencia si se ingresó un operador inválido o si se intentó dividir entre cero.

### 2.4. Actividad 4 (Propuesta): Resuelve

Una agencia de seguros para autos asigna costos mensuales en base al sexo y edad del conductor. Los varones menores de 25 años pagan 1000 soles, los de 25 a más pagan 700 soles. Las mujeres de 21 años o menos pagan 500 y las que tienen más de 21 años pagan 300 soles. Realizar un programa en usando PSeInt con estructuras selectivas multiples, que solicite la edad y sexo de la persona, luego de acuerdo con lo mencionado muestre el costo mensual del seguro en pantalla.

## Análisis del problema:

- **A. Datos de entrada** :

   - a. **Edad** del conductor: Un número entero que indicará cuántos años tiene la persona.

   - b. **Sexo** del conductor: Puede ser **varón** o **mujer** (representado como "V" o "M" en el programa).

- **B. Condiciones para el cálculo del costo del seguro** :

   - a. **Varones** :

      - i. Si son menores de **25 años** , el costo del seguro es de **1000 soles** .

      - ii. Si tienen **25 años o más** , el costo es de **700 soles** .

   - b. **Mujeres** :

      - i. Si tienen **21 años o menos** , el costo del seguro es de **500 soles** .

      - ii. Si tienen **más de 21 años** , el costo es de **300 soles** .

- **C. Resultado esperado** :

   - a. El programa debe mostrar el **costo mensual del seguro** basado en los valores de edad y sexo que se ingresen.

## 3. Ejercicios adicionales:

- A. Dado el peso, la altura y el sexo, de unos estudiantes. Realizar un programa en PSeInt que determine la cantidad de vitaminas que deben consumir estos estudiantes, en base al siguiente criterio:

   - Si son varones, y su estatura es mayor a 1.60 m, y su peso es mayor o igual a 70 kg, su dosis, serán: 20% de la estatura y 80% de su peso. De lo contrario, la dosis será la siguiente: 30% de la estatura y 70% de su peso.

   - Si son mujeres, y su estatura es mayor de 1.50 m y su peso es mayor o igual a 60 kg, su dosis será: 25% de la estatura y 75% de su peso. De lo contrario, la dosis será: 35% de la estatura y 65% de su peso. La dosis debe ser expresada en gramos.

### Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|05 puntos||
|Actividad 2|05 puntos||
|Actividad 3|05 puntos||
|Actividad 4|05 puntos||
|**Total**|**20puntos**||

### Bibliografía

- Aprender a Programar. Ejemplos en PSeInt : Edición 4. (2023). (n.p.): José Luis Rodríguez Muñoz.

- Gómez Jiménez, E., Aguilera Jinesta, R. (2023). Metodología de la programación: conceptos, lógica e implementación. España: Marcombo.

- Programación Básica: En lenguaje natural. (2019). (n.p.): RedUsers.

- Gómez, E. (2022). Metodología de la programación: Conceptos, lógica e implementación. Colombia: Alpha Editorial.

- Rodríguez Rancel, M., Hernández González, C. (2015). Aprende a programar con pseudocódigo, diagramas de flujo y ejercicios de ejemplo resueltos en C: Algoritmos y lógica para aprender programación desde cero. España: Editorial aprenderaprogramar.com.
