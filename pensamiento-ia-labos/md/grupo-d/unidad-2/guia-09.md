# GUÍA DE LABORATORIO #09

## Tema

- Estructuras Secuenciales

## Competencias

- Entiende concepto de variable; entrada, procesamiento y salida de datos

- Resuelve problemas con estructuras secuenciales

- Crea algoritmos secuenciales en pseudocódigo

## Materiales/Herramientas

- Computador

- Software PSeint

## Fundamento teórico

### 1.1. Introducción al Pensamiento Computacional

#### 1.1.1. Definición

El pensamiento computacional es una competencia fundamental en la era digital, que involucra el uso de conceptos de la informática para resolver problemas de manera eficaz y eficiente. Este tipo de pensamiento se refiere a la habilidad de formular problemas de manera que una computadora (u otro ser humano) pueda resolver, utilizando un conjunto de técnicas y herramientas específicas. El pensamiento computacional no solo es esencial para los profesionales en informática, sino que también es una habilidad valiosa para cualquier persona que desee enfrentar problemas complejos de manera eficaz.

#### 1.1.2. Capacidades asociadas al pensamiento computacional

Existe cierto consenso en relación con que el pensamiento computacional va más allá de programar o codificar e implica todo un proceso previo, de formulación y análisis del problema, como así también de diseño y de evaluación de soluciones.

- Capacidad de pensar de forma algorítmica,

- Capacidad de pensar en términos de descomposición,

- Capacidad de pensar en generalizaciones, identificando y haciendo uso de patrones,

- Capacidad de pensar en términos abstractos y elección de buenas representaciones,

- Capacidad de pensar en términos de evaluación.

Figura 1

#### 1.1.3. Técnicas asociadas con el pensamiento computacional

Más allá de las capacidades que configuran el pensamiento computacional, de manera complementaria existen una serie de técnicas asociadas a su desarrollo cuya función es ordenar y favorecer el trabajo cognitivo. Son las siguientes:

- **Reflexión** : se define como la habilidad de llevar a cabo juicios argumentados sobre situaciones que tengan cierto grado de complejidad.

- **Análisis** : para analizar una situación problemática, se acude a una serie de herramientas auxiliares como dividir en partes de menor complejidad los componentes de un problema (descomponer), reducir aspectos de complejidad (abstraer), identificar los procesos y buscar elementos patrones (generalizar). Se trata de utilizar la capacidad analítica, apelando a la lógica, para comprender plenamente el problema y así avanzar en su solución.

- **Diseño** : es una técnica que se aplica al proceso de desarrollo de una solución efectiva y eficiente de un problema. El diseño implica creatividad debido a que es necesario ver desde distintos puntos de vista un mismo problema, satisfacer las necesidades o deseos y adaptarse a un contexto que la hace posible y sustentable.

- **Programación** : todo diseño de una solución a un problema debe ser programado para que una computadora pueda automatizar el proceso. A esta traducción de la solución, realizada utilizando los recursos de un lenguaje computacional, se le debe aplicar un proceso de revisión técnica funcional que la evalúe en función de garantizar su funcionamiento correcto en todas las condiciones de trabajo.

- **Aplicación** : se basa en la adopción de soluciones existentes para satisfacer las necesidades de otro contexto. Esta habilidad implica el uso de la capacidad de generalizar debido a que se deben identificar patrones y realizar conexiones a efectos de adoptar lo preexistente.

Figura 2

### 1.2. Estructuras Secuenciales

Las estructuras secuenciales son uno de los pilares fundamentales de la programación. Se refieren a la ejecución de instrucciones en un orden lineal y secuencial, donde cada instrucción se ejecuta después de la anterior. Este tipo de estructura es esencial para desarrollar algoritmos y programas que sigan un flujo lógico y predecible.

#### 1.2.1. Variables

Las variables son espacios de memoria en los que se pueden almacenar datos que pueden cambiar durante la ejecución de un programa. Cada variable tiene un nombre y un tipo de dato asociado que determina qué tipo de información puede almacenar (números, texto, booleanas).

#### 1.2.2. Algoritmo

Un algoritmo es una secuencia finita de instrucciones bien definidas que se pueden utilizar para resolver un problema computacional. Proporciona un procedimiento paso a paso que convierte una entrada en una salida deseada. Los algoritmos normalmente siguen una estructura lógica:

- **Entrada** : Los datos de entrada son la información que el usuario proporciona al programa para que este realice un procesamiento. Estos datos pueden ser introducidos mediante el teclado, archivos, sensores, u otras fuentes.

- **Procesamiento** : El procesamiento es la fase en la que el programa toma los datos de entrada y realiza operaciones sobre ellos para producir un resultado. Estas operaciones pueden incluir cálculos matemáticos, manipulación de texto, entre otros.

- **Salida** : Los datos de salida son los resultados obtenidos después del procesamiento. Estos resultados se muestran al usuario o se almacenan para su uso posterior.

#### 1.2.3. Representación de un Algoritmo

- **Pseudocódigo:** El pseudocódigo es una representación textual simplificada de un algoritmo que utiliza una estructura similar a la programación, pero sin la sintaxis rígida de un lenguaje específico. Es una herramienta útil para planificar y comunicar ideas antes de implementar el código real.

- **Diagramas de Flujo:** Los diagramas de flujo son representaciones gráficas de un algoritmo, donde cada paso se muestra como una figura geométrica (rectángulos para procesos, rombos para decisiones, etc.) conectada por flechas que indican el flujo de la ejecución.

#### 1.2.4. PSeint

PSeInt es una herramienta para asistir a un estudiante en sus primeros pasos en programación. Mediante un simple e intuitivo pseudolenguaje en español (complementado con un editor de diagramas de flujo), le permite centrar su atención en los conceptos fundamentales de la algoritmia computacional, minimizando las dificultades propias de un lenguaje y proporcionando un entorno de trabajo con numerosas ayudas y recursos didácticos.

Figura 3

## Aplicación de la guía

### 2.1. Actividad 1: Crear un programa que pregunte por el nombre y apellidos de un usuario y devuelva un saludo.

A continuación, escribimos nuestro primer programa en Pseint para ello seguiremos los siguientes pasos:

- Abrimos el programa PSeint (fig. 3), la pantalla está dividida tres partes principales: un editor donde se escribirá el código, una paleta de comandos ubicada en la parte derecha y un bloque para mensajes de error en la parte inferior.

- Como primer paso presionamos el botón guardar, escribimos un nombre para el archivo _“Saludo.psc_ ” y procedemos a escribir nuestro código.

- Análisis del problema

|**Etapa**|**Descripción (variables, cálculos,etc.)**|**Ejemplo**||
|---|---|---|---|
|Entrada|• Nombres • Apellidos|• Satoshi • Nakamoto||
|Proceso|Concatenar o juntar textos|Mucho gusto Nakamoto|Satoshi|
|Salida|Escribir saludo|Mucho gusto Nakamoto|Satoshi|

- Para este primer programa requerimos los comandos escribir y leer, para usarlos bastara con hacer clic sobre el comando, este escribirá el código por nosotros, luego nos tocara editar el nombre de la variable _“lista_de_variables”_ en caso de lectura y el caso de escritura modificar el texto _“lista_de_expresiones”_ . Por otro lado, también puede escribir el comando directamente en el editor cuando esta familiarizado con la sintaxis.

- Continuar agregando comandos hasta culminar con el programa que debería quedar como la imagen siguiente:

- Una vez terminado podemos ejecutar o correr el programa haciendo clic en el botón verde.

- También podemos ver la representación grafico mediante un diagrama de flujo presionando el botón dibujar diagrama

### 2.2. Actividad 2: Crear un programa que permita calcular la suma, resta, multiplicación, división y división modular o residuo de dos números.

- Análisis del problema

|**Etapa**|**Descripción (variables, cálculos, etc.)**|**Ejemplo**|
|---|---|---|
|Entrada|• numero1 • numero2|• 21 • 5|
||• suma = Numero1 + Numero2 • resta = Numero1 - Numero2|• suma = 21 + 5 = 26 • resta = 21 – 5 = 16|
|Proceso|• producto = Numero1 * Numero2 • division = Numero1 / Numero2 • residuo=Numero1 MOD Numero2|• producto = 21 * 5 = 105 • division = 21 / 5 = 4.2 • residuo=21 Mod 5=1|
|Salida|Escribir suma, resta, producto, division, residuo|Escribir resultados 26, 16, 105, 4.2 y 1|

- Para este programa usaremos un nuevo comando “Asignar”, este nos permitirá asignar o guardar el resultado de una expresión determinada (suma, resta, etc.) en una variable

- El algoritmo quedara de la siguiente forma, nótese además que incluimos comentarios para entender claramente el programa, los comentarios no son tomados en cuenta y se anteceden por “//” (doble slash)

- Ejecución del programa

- Diagrama de flujo

### 2.3. Actividad 3: Escribir un programa que permita calcular el área de un rectángulo.

## • **Análisis**

|**Etapa**|**Descripción (variables, cálculos, etc.)**|**Ejemplo**|
|---|---|---|
|Entrada|• ladoMayor • ladoMenor|• 20 • 10|
|Proceso|• area = ladoMayor * ladoMenor|• area = 20*10 = 200|
|Salida|Escribir area|Escribir 200|

## • **Algoritmo**

## • **Ejecución**

## • **Diagrama de flujo**

- 2.4. **Actividad 4 (Propuesta):** Crear un programa que calcule el promedio aritmético de tres notas.

- **2.5. Actividad 5 (Propuesta):** Escribir un programa que solicite un numero de tres dígitos y muestre la suma de sus dígitos. Por ejemplo, para el numero 345 la respuesta seria 3+4+5 = 12

## Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|04 puntos||
|Actividad 2|04 puntos||
|Actividad 3|04 puntos||
|Actividad 4|04 puntos||
|Actividad 5|04 puntos||
|**Total**|**20puntos**||

## Bibliografía

- Bordignon, F. R. A., & Iglesias, A. A. (2020). Introducción al pensamiento computacional. Universidad Pedagógica Nacional y Educar SE.

- Wing, J. M. (2006). Computational Thinking. Communications of the ACM, 49(3), 33-35

- <u>https://pseint.sourceforge.net/</u>

- https://www.geeksforgeeks.org/fundamentals-of-algorithms/
