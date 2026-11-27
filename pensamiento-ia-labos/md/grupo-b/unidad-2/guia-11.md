# GUÍA DE LABORATORIO #11

## Tema

- **Estructuras selectivas anidadas y múltiples usando Google Colab**

## Competencias

- Aplicar estructuras selectivas anidadas y múltiples en la resolución de problemas.

- Desarrollar algoritmos utilizando la herramienta Google Colab.

- Implementar soluciones con estructuras de decisión complejas.

## Materiales/Herramientas

- Computadora con acceso a Internet.

- Acceso a Google Collaboratory (COLAB).

## Fundamento teórico

### 1.1. Estructuras selectivas anidadas

Las estructuras selectivas anidadas permiten evaluar decisiones de forma secuencial. Se usan cuando una decisión depende de una evaluación previa. Cada condición puede llevar a nuevas decisiones dentro de su bloque. Esta estructura es fundamental cuando hay múltiples factores que deben ser evaluados de manera interdependiente.

Ejemplo: Si un paciente tiene fiebre, se evalúa si tiene tos o dolor muscular. Dependiendo de esa combinación de síntomas, se decide si el paciente necesita un tratamiento leve o fuerte.

### 1.2. Estructuras selectivas Múltiples

Las estructuras selectivas múltiples permiten evaluar una condición contra varios casos posibles y tomar decisiones diferentes para cada caso. Esto es útil cuando se tienen categorías mutuamente excluyentes, donde solo una opción es válida a la vez.

Ejemplo: Determinar el tipo de atención médica según el código ingresado

## Aplicación de la guía

### 2.1. Actividad 1: Clasificación de niveles de glucosa en sangre con selección

## múltiple

- Objetivo: Implementar un algoritmo que permita al usuario ingresar un código que clasifique el nivel de glucosa en sangre de un paciente y sugiera las acciones correspondientes según el nivel ingresado.

- Pasos:

   1. Mostrar un menú con los diferentes niveles de glucosa en sangre y sus códigos asociados:

      - 1: Menos de 70 (Hipoglucemia)

      - 2: Entre 70 y 99 (Normal)

      - 3: Entre 100 y 125 (Prediabetes)

      - 4: Mayor o igual a 126 (Diabetes)

   2. Pedir al usuario que ingrese el código correspondiente al nivel de glucosa.

   3. Usar una estructura selectiva múltiple ( `Segun` ) para clasificar el nivel de glucosa según el código ingresado.

   4. Mostrar el diagnóstico y las acciones recomendadas según el código ingresado.

   5. Manejar los casos en que el usuario ingrese un código no válido mostrando un mensaje de error.

- Escribir el resultado.

### 2.2. Actividad 2: Evaluación de síntomas respiratorios

- Objetivo: Crear un algoritmo que evalúe los síntomas respiratorios y determine si un paciente debe ser hospitalizado.

- Pasos:

   1. Leer la temperatura, la frecuencia respiratoria y si hay dolor de pecho.

   2. Usar una estructura selectiva anidada para decidir:

      - Si la temperatura es mayor a 38°C y la frecuencia respiratoria es alta, verificar si hay dolor de pecho.

      - Si hay dolor de pecho, recomendar hospitalización.

      - Si no hay dolor de pecho, recomendar reposo.

   - Si la temperatura es menor a 38°C, no hay síntomas graves.

- Escribir el resultado.

### 2.3. Actividad 3 (Propuesta): Clasificación de severidad de quemaduras

- Objetivo: Diseñar un algoritmo para clasificar la severidad de quemaduras según el área afectada y la profundidad.

- Descripción: Leer el porcentaje del cuerpo afectado y la profundidad de la quemadura (superficial, parcial, total).

- Tareas:

   - Si la quemadura afecta más del 20% del cuerpo y es profunda, indicar tratamiento inmediato.

   - Si la quemadura es superficial o afecta menos del 20%, indicar cuidado ambulatorio.

### 2.4. Actividad 4 (Propuesta): Decisión sobre transfusión de sangre

- Objetivo: Implementar un algoritmo que evalúe si un paciente necesita una transfusión de sangre según su nivel de hemoglobina y otros síntomas.

- Descripción: Leer el nivel de hemoglobina y si el paciente presenta mareos o fatiga extrema.

- Tareas:

- Si el nivel de hemoglobina es menor a 7 g/dL y presenta síntomas, recomendar transfusión.

- Si sólo presenta síntomas sin anemia severa, recomendar observación.

## Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|05 puntos||
|Actividad 2|05 puntos||
|Actividad 3|05 puntos||
|Actividad 4|05 puntos||
|**Total**|**20puntos**||

## Bibliografía

- Gómez, P. (2021). Fundamentos de Programación en Pseudocódigo con PSEint. Editorial Universitaria.

- Smith, J. (2019). Lógica de Programación y Algoritmos en Ciencias de la Salud. Ediciones Médicas.
