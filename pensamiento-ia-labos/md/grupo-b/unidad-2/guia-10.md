# GUÍA DE LABORATORIO # 10

## Tema:

## ESTRUCTURAS SELECTIVA SIMPLES Y DOBLES

## Competencias:

- **Comprensión de Estructuras Selectivas:** Identificar y aplicar estructuras selectivas simples y dobles para controlar el flujo de un programa.

- **Resolución de Problemas:** Desarrollar la habilidad de resolver problemas utilizando estructuras de control condicionales.

- **Desarrollo de Algoritmos:** Diseñar algoritmos que incluyan decisiones basadas en condiciones lógicas.

- **Codificación Eficiente:** Escribir código claro y eficiente que use correctamente las estructuras selectivas.

- **Depuración y Pruebas:** Habilidad para depurar código y realizar pruebas de las estructuras selectivas en diferentes escenarios.

## Materiales/Herramientas

- Python

## Fundamento teórico

Las estructuras selectivas permiten a los programas tomar decisiones en función de condiciones. Esto es clave en el análisis de datos médicos, donde las decisiones deben tomarse en base a parámetros médicos.

### SIMPLES:

- **Definición:** Son aquellas que permiten que el programa elija una dirección de flujo basado en una única condición.

- **Uso Común:** Se utilizan cuando se necesita ejecutar una acción solo si una condición específica es verdadera.

- **Operadores Relacionales:** Utilizados para comparar valores (==, !=, >, <, >=, <=).

### DOBLES:

- **Definición:** Son aquellas que permiten al programa elegir entre dos direcciones de flujo basadas en una condición.

- **Uso Común:** Se emplean cuando hay una acción a realizar si la condición es verdadera y otra diferente si es falsa.

### Estructura selectiva simple

## 1. Implementar un programa que determine si un número es positivo.

**#Solicitar al usuario un número.**

nro = int(input('Ingrese el numero: '))

**#Verificar si el número es mayor que cero y imprimir mensaje.**

if nro > 0:

print('es positivo')

## 2. Determinar si un número es positivo, negativo o cero

**# Número Positivo, Negativo o Cero**

numero = float(input("Ingresa un número: "))

if numero > 0:

print("El número es positivo.")

if numero < 0:

print("El número es negativo.")

if numero == 0:

print("El número es cero.")

### Estructuras selectivas dobles

**1.** Escribir un programa que determine si un numero de 3 dígitos es igual a la suma de los cubos de sus dígitos Ejemplos

|**Nro**|**Dig1**|**Dig2**|**Dig3**|**Cubo**|**Cubo**|**Cubo**|**Suma**|**Resultado**|
|---|---|---|---|---|---|---|---|---|
|||||**Dig1**|**Dig2**|**Dig3**|||
|373|3|7|3|27|343|27|397|No es igual|
|153|1|5|3|1|125|27|153|Si es Igual|

**# Leer el número**

nro = int(input('Ingrese un número: '))

**#Desconponer los dígitos**

u = nro % 10 d = (nro // 10) % 10 c = nro // 100

**#Sumar los cubos de cada digito**

suma = u**3 + d**3 + c**3 if suma == nro:

mensaje = 'Es igual a la suma del cubo de sus dígitos' else:

mensaje = 'No es igual a la suma del cubo de sus dígitos'

print(suma,' ',mensaje)

## 2. Crear un programa que clasifique un número como positivo, negativo o cero.

**#Solicitar al usuario un número.**

nro = int(input('Ingrese el numero: '))

**#Verificar si el número es positivo, negativo o cero e imprimir mensaje.**

if nro > 0:

print(' El número es positivo') elif nro < 0: print(' El número es negativo') else:

print(' El número es cero')

## Aplicación de la guía

### Actividad 1: Evaluación de Mejora en Pacientes

En una clínica, se evalúa el porcentaje de mejora de los pacientes tras un tratamiento. Se considera que un paciente tiene una mejora significativa si el porcentaje de mejora es mayor al 10%.

Instrucciones:

- Crea un programa que lea el porcentaje de mejora de un paciente.

- Si el porcentaje es mayor a 10%, imprime "Mejora significativa".

- De lo contrario, imprime "Mejora marginal".

### Actividad 2: Clasificación de Pacientes según Edad y Signos Vitales

Diseña un programa que clasifique a los pacientes de acuerdo a su edad y sus signos vitales, determinando si requieren atención inmediata o no.

- Niño: 0-12 años

- Adolescente: 13-17 años

- Adulto: 18-64 años

- Adulto Mayor: 65+ años

Además, si los signos vitales (temperatura corporal) son mayores a 38°C, se considera una emergencia y se requiere atención inmediata.

Instrucciones:

- Crea un programa que lea la edad del paciente y determine su categoría.

- Luego, evalúa si la temperatura es mayor a 38°C para determinar si el paciente requiere atención inmediata.

### Actividad 3: Análisis de Índices de Salud para Diagnóstico Complejo

En una clínica, se usan múltiples indicadores de salud para diagnosticar el estado de un paciente. El diagnóstico se basa en los siguientes criterios:

- Colesterol total: Normal < 200 mg/dL, Alto ≥ 240 mg/dL

- Glucosa en ayunas: Normal < 100 mg/dL, Diabetes ≥ 126 mg/dL

- Presión arterial sistólica: Normal < 120 mmHg, Alta ≥ 140 mmHg

- Índice de Masa Corporal (IMC): Bajo peso < 18.5, Sobrepeso ≥ 25

El programa debe determinar si el paciente se encuentra en una condición de salud general aceptable o requiere atención inmediata si dos o más de los valores se encuentran fuera del rango normal.

Instrucciones:

- Solicita al usuario ingresar los valores de colesterol, glucosa, presión arterial e IMC.

- Verifica si dos o más valores están fuera del rango normal.

- Si se cumple esta condición, imprime "Requiere atención inmediata", de lo contrario, imprime "Salud aceptable".

### Actividad 4: Diagnóstico Automático de Hipertensión y Diabetes Combinadas

Diseña un programa que evalúe a un paciente para diagnosticar hipertensión y diabetes basándose en los valores de presión arterial y glucosa. El programa debe tomar decisiones basadas en las siguientes reglas:

- Hipertensión: Presión sistólica ≥ 140 mmHg o presión diastólica ≥ 90 mmHg.

- Diabetes: Glucosa en ayunas ≥ 126 mg/dL.

El programa debe clasificar al paciente en una de las siguientes categorías:

- Hipertenso: Si cumple solo con los criterios de hipertensión.

- Diabético: Si cumple solo con los criterios de diabetes.

- Hipertenso y Diabético: Si cumple con ambos.

- Saludable: Si no cumple con ninguno de los criterios.

Instrucciones:

- Solicita al usuario ingresar los valores de presión arterial sistólica, diastólica y glucosa en ayunas.

- Evalúa si el paciente es hipertenso, diabético o ambas condiciones.

- Muestra el diagnóstico.

### Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|05 puntos||
|Actividad 2|05 puntos||
|Actividad 3|05 puntos||
|Actividad 4|05 puntos||
|**Total**|**20 puntos**||

### Bibliografía

- https://flexbooks.ck12.org/cbook/ck-12-conceptos-de-%C3%A1lgebra-nivelb%C3%A1sico-en-

espa%C3%B1ol/section/5.11/primary/lesson/interpolaci%C3%B3n-yextrapolaci%C3%B3n-lineal-bsc-alg-spn/

- Algorítmica y programación un enfoque practico

- https://academiarafavilchez.com/calculadora-

   - interpolacion/#:~:text=La%20interpolaci%C3%B3n%20lineal%20consiste%20en,val ores%20intermedios%20seg%C3%BAn%20esta%20recta.
