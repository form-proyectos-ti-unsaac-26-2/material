# GUÍA DE LABORATORIO #06 ÉTICA EN EL USO DE DATOS: BIG DATA Y DATOS ABIERTOS EN EXCEL

### I. Competencias

- Comprender conceptos básicos de Big Data y datos abiertos.

- Utilizar herramientas de Excel para analizar y gestionar grandes conjuntos de datos.

- Aplicar técnicas básicas de análisis de datos y visualización en Excel.

- Reconocer y aplicar principios de ética digital en el manejo y análisis de datos de salud.

## II. Materiales/Herramientas

- Ms. Excel

## III. Fundamento teórico

## III.1 Big Data

Se refiere a conjuntos de datos que son tan grandes y complejos que las herramientas de procesamiento de datos convencionales no son adecuadas para manejar la información.

Para que Big Data sea efectivo, se deben llevar a cabo tres pasos clave:

- Integración. - Big Data recopila grandes volúmenes de datos, que pueden alcanzar terabytes o incluso petabytes, provenientes de diversas fuentes. Estos datos necesitan ser recibidos, procesados y convertidos al formato requerido por los usuarios empresariales y analistas para que puedan comenzar su análisis.

- Gestión. - Big Data requiere una cantidad significativa de almacenamiento, ya sea en la nube, en instalaciones locales o en una combinación de ambas. Además, los datos deben guardarse en el formato necesario y estar disponibles en tiempo real. Cada vez más, las organizaciones optan por soluciones en la nube para beneficiarse de la computación y la escalabilidad sin límites.

- Análisis. - El paso final consiste en analizar los datos de Big Data y tomar decisiones basadas en los resultados. De lo contrario, la inversión no será justificada. Además de revisar los datos, es crucial comunicar y compartir información valiosa con toda la organización de manera comprensible. Esto incluye utilizar herramientas para generar visualizaciones de datos, como gráficos y paneles.

## III.2 Datos Abiertos

Son datos que se encuentran disponibles públicamente y pueden ser utilizados, reutilizados y redistribuidos por cualquier persona, sin restricciones legales, por tanto el uso de estos datos con fines de análisis e investigación es considerado ético.

En el Perú existe la Plataforma Nacional de Datos Abiertos (PNDA) que publica datos gubernamentales, en formato digital, estandarizados, comparables, accesibles desde internet. Con el objetivo de ser útiles para crear aplicaciones, realizar investigación, analizar oportunidades de negocio, desarrollar la economía, ejercer el control ciudadano y diseñar política pública, sin comprometer el derecho a la protección de los datos personales de los ciudadanos.

## III.3 Microsoft Excel

Es una aplicación de hoja de cálculo desarrollada por Microsoft. Aunque Excel no está diseñado para manejar conjuntos de datos grandes o complejos como lo haría un software especializado en Big Data, ofrece funcionalidades útiles para realizar análisis preliminares. Sus capacidades de importación de datos, fórmulas, tablas dinámicas y gráficos permiten a los usuarios gestionar y analizar datos de tamaño moderado.

## III.3.1. Funciones

Es una fórmula predefinida que realiza cálculos utilizando valores específicos, denominados argumentos, en un orden determinado. Estas funciones abarcan desde operaciones matemáticas básicas hasta complejos análisis estadísticos y financieros, facilitando enormemente el trabajo con datos

_Fig. 1 Partes de una función_

## IV. Aplicación de la guía

Para efectos de esta guía nos centraremos en el paso de análisis del Big Data. Utilizaremos conjuntos de datos ( _dataset)_ disponibles en la PNDA.

El _dataset_ que utilizaremos es el listado de pacientes nuevos que acuden al INEN, este archivo estará adjunto a esta guía en classroom. Cada registro corresponde a un paciente admitido, este _dataset_ cuenta con los siguientes campos:

- Historia: Corresponde al número de historia clínica del paciente.

- Fecha de filiación: Es la fecha de admisión del paciente en el INEN.

- Sexo: Corresponde al sexo del paciente

- Edad: Es la edad que tiene el paciente en la fecha de admisión.

- Código Ubigeo del lugar de residencia: Es el código de ubigeo de la residencia del paciente.

- Lugar residencia: Es la descripción del ubigeo de la residencia del paciente.

- Cantidad de atenciones en cex: Es la cantidad de atenciones recibidas en consulta externa.

- Fecha de corte: Fecha en que se generó la información.

## IV.1 Actividad 1: Importar y limpiar el conjunto de datos

Importar el archivo de datos en Excel y realizar una limpieza básica.

1. Abrir Excel y seleccionar la pestaña "Datos" en la cinta de opciones.

2. Hacer clic en "Desde un archivo de texto/CSV" para importar el archivo de datos. Seleccionar el archivo CSV proporcionado. Un archivo CSV (valores separados por comas) es un tipo especial de archivo que se puede crear o editar en Excel. En lugar de almacenar la información en columnas, los archivos CSV almacenan datos separados por comas.

3. Excel abrirá un diálogo de importación. Selecciona la opción “Delimitados”. Luego la opción “Coma”. Finalmente, para cada columna selecciona un tipo o formato de dato.

   - a. Puedes seleccionar todas las columnas manteniendo presionada la tecla “shift” y luego hacer clic en la primera y última columna. Las columnas se sombrearán de color negro. Selecciona el tipo de dato “Texto”.

_Fig. 2 Asistente para importar texto_

4. Verificar que los datos se carguen correctamente en una tabla. Hacer clic en "Cargar".

5. Una vez cargado el archivo, revisar los datos en la hoja de cálculo:

6. Eliminar columnas innecesarias si es necesario. Para ello, selecciona la columna, haz clic derecho y selecciona "Eliminar".

7. Revisar y corregir errores en los datos (por ejemplo, valores nulos o incorrectos). Puedes utilizar la funcionalidad de "Buscar y reemplazar" para corregir errores comunes.

8. Corregir el formato de algunas columnas. Por ejemplo, de la columna “Fecha de filiación”.

   - a. Para ello agrega una columna con el nombre “FechaFiliacion” haciendo clic derecho, insertar columnas.

   - b. En esta nueva columna, utiliza la función Texto para dar el formato correcto.

## =TEXTO(D2;"####-##-##")

9. Repite el paso anterior para la columna “Fecha de corte”

10. Analizando la columna “Lugar_residencia”, vemos que hace referencia al departamento, provincia y distrito. Para un mejor análisis de datos vamos a

dividir esa columna en 3. Para ello inserta 3 columnas (Departamento, Provincia, Distrito) al costado de la columna “Lugar de residencia”.

11. Selecciona la columna “Lugar_residencia”. Luego haz clic en la opción Datos>texto en columnas. Selecciona la opción “Delimitado”. Como separador ingresa el “-“en la opción “otros”.

## IV.2 Actividad 2: Análisis descriptivo de datos.

Para calcular estadísticos básicos haremos uso de algunas funciones de Excel (SI, SUMAR, CONTAR, y PROMEDIO).

- **IV.2.1. Función SI** . - La función SI permite realizar una evaluación condicional de los datos y devolver un valor si la condición es verdadera, y otro valor si es falsa.

=SI(prueba_lógica, valor_si_verdadero, valor_si_falso)

## a) Ejercicio clasificación de edad

1. Agregar una nueva columna en la hoja de cálculo llamada "RANGO_EDAD".

2. En la celda de la nueva columna (por ejemplo, J2), escribe la siguiente fórmula para clasificar las edades en rangos:

=SI(E2<=20, "0-20", SI(E2<=40, "21-40", SI(E2<=60, "41-60", "61+")))

      - E2 es la celda que contiene la edad, reemplaza dicha celda según corresponda.

      - La fórmula clasifica las edades en cuatro rangos: 0-20, 21-40, 41-60, y 61+.

   3. Arrastrar la fórmula hacia abajo para aplicarla a todas las celdas de la columna

- **IV.2.2. Función SUMAR y SUMAR.SI. -** La función SUMAR suma todos los números en un rango de celdas. La función SUMAR.SI suma las celdas que cumplen con un criterio específico.

## a) Ejercicio total de atenciones

1. Seleccionar una celda vacía donde calcular el total de atenciones.

2. Escribe la siguiente fórmula

=SUMAR(H2:H1000)

- H2:H1000 es el rango de celdas que contiene la cantidad de atenciones. Reemplázalo con el rango de datos real que correspondan en tu hoja de cálculo.

## b) Total de atenciones para una ubicación específica

1. Agregar una nueva celda para calcular el total de atenciones para un departamento específico (por ejemplo, Lima)

2. Escribe la siguiente fórmula

=SUMAR.SI(G2:G1000, "Lima", H2:H1000)

   - G2:G1000, es el rango de celdas que contiene los nombres de los lugares de residencia.

   - "Lima" es el lugar específico para el cual deseas calcular el total de atenciones.

   - H2:H1000, es el rango de celdas que contiene la cantidad de atenciones.

   - Recuerda cambiar los rangos y valores según tu hoja de cálculo.

- **IV.2.3. Función CONTAR. -** Cuenta el número de celdas que contienen números en un rango.

## a) Contar el total de registros que tiene el conjunto de datos

1. Seleccionar una celda vacía donde calcular el total de registros

2. Escribe la siguiente fórmula:

## =CONTAR(E2:E1000)

   - E2:E1000, es el rango de celdas que contiene números.

   - `o` Recuerda que la función CONTAR cuenta solo números.

- **IV.2.4. Función PROMEDIO. -** Calcula la media aritmética de los números en un rango

## a) Ejercicio promedio de edad

1. Seleccionar una celda vacía donde calcular el promedio de edad.

2. Escribe la siguiente fórmula:

=PROMEDIO(E2:E1000)

`o` E2:E1000, es el rango de celdas que contiene las edades

## IV.3 Actividad 3 (Propuesta): Resuelve los siguientes ejercicios

- Contar cuántos pacientes son de sexo femenino.

- Contar cuántos pacientes son de sexo masculino.

- Calcular la suma total de atenciones para pacientes que residen en una ubicación específica dado el departamento, provincia y distrito, por ejemplo (Lima, Lima, Lima). Averigua la función SUMAR.SI.CONJUNTO.

- Calcular el promedio de la cantidad de atenciones para los pacientes cuyo sexo es "Masculino".

- Crear una nueva columna llamada "Categoría Edad"

   - "Joven" si la edad es menor o igual a 30 años.

   - "Adulto" si la edad está entre 31 y 60 años.

   - "Adulto mayor" si la edad es mayor a 60 años **.**

- Calcular el promedio de atenciones dado un departamento, provincia y distrito, por ejemplo (Lima, Lima, Lima).

- Cuántos pacientes tienen entre 30 y 40 años de edad y son de sexo masculino.

- Calcular la cantidad de atenciones en consultorio externo (CEX)solo para pacientes cuya "Fecha de filiación" es en el año 2023.

## IV.4 Actividad 4 (Propuesta): Responde la siguiente pregunta

En el contexto del análisis de datos de salud, como el que se realiza en esta guía, ¿cuáles son algunas **consideraciones éticas importantes** que deben tenerse en cuenta al manejar y compartir datos personales de pacientes? Proporcione ejemplos específicos relacionados con la privacidad y el consentimiento.

### V. Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|05 puntos||
|Actividad 2|05 puntos||
|Actividad 3|05 puntos||
|Actividad 4|05 puntos||
|**Total**|**20 puntos**||

## VI. Bibliografía

- Plataforma Nacional de Datos Abiertos. (2024, 3 abril). Plataforma Nacional de Datos Abiertos (PNDA). Recuperado 20 de agosto de 2024, de <u>https://www.gob.pe/datosabiertos</u>

- Definición del Big Data: ejemplos y ventajas | Google Cloud. (n.d.). Recuperado de <u>https://cloud.google.com/learn/what-is-big-data?hl=es</u>
