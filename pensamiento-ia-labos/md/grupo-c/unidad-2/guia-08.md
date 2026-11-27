# GUÍA DE LABORATORIO #08

## Tema

## ● **Gestión y Visualización de Datos**

## Competencias

- El estudiante es capaz de aprender a usar unas de las herramientas más demandadas a nivel Global.

- El estudiante es capaz de utilizar la herramienta Buscar Objetivo.

- El estudiante es capaz de utilizar la Segmentación de Datos

- El estudiante es capaz de utilizar las Tablas Dinámicas

## Materiales/Herramientas

- Computadoras con acceso a Internet.

- Documentación del sistema operativo Windows.

- Procesador de textos.

- Bloc de notas y lápiz.

## Fundamento teórico

### 1.1. Conceptos

**Buscar objetivo.-** Si conoce el resultado que desea de una fórmula, pero no está seguro del valor de entrada que necesita la fórmula para obtener ese resultado, use la característica Buscar objetivo. Por ejemplo, supongamos que necesita un préstamo. Ya sabe cuánto dinero desea, cuánto tiempo quiere tardar en pagar el préstamo y cuánto puede permitirse pagar cada mes. Puede usar Buscar objetivo para determinar la tasa de interés que necesitará asegurar para cumplir con su objetivo de préstamo.

<u>https://support.microsoft.com/es-es/office/usar-buscar-objetivo-para-encontrar-elresultado-que-desea-ajustando-un-valor-de-entrada-320cb99e-f4a4-417f-b1c34f369d6e66c7#:~:text=En%20la%20pesta%C3%B1a%20Datos%2C%20en,el%2 0f%C3%B3rmula%20que%20desea%20resolver</u>

**Las tablas dinámicas. -** Son un excelente modo de resumir, analizar, explorar y presentar los datos. Las tablas dinámicas son muy flexibles y se pueden ajustar rápidamente en función de cómo se tengan que mostrar los resultados. También

puede crear gráficos dinámicos a partir de tablas dinámicas que se actualizan automáticamente al hacerlo las tablas dinámicas.

## Aplicación de la guía

### 2.1. Actividad 1: Buscar Objetivo

Abrimos el archivo proporcionado por el docente: **01- Excel+Buscar+Objetivo.xlsx**

Ahora llenamos la información como se muestra en la imagen, una inversión a tasa fija a un año con el monto invertido que es 120 000 dólares (el formato ya reconoce el símbolo del $ en la celda), la tasa está en 0 por que no la conocemos aun, y el rendimiento que nos otorgó la inversión es de 17 000 dólares.

Buscar objetivo trabaja ya por una celda formulada es decir que ya tenga establecida una fórmula de cálculo de algún valor. Ahora escribimos la fórmula para calcular el rendimiento con una determinada tasa.

Una forma de encontrar el resultado sería variar la tasa para aproximarnos al rendimiento, por ejemplo, colocaremos 13 en tasa.

Para aproximarnos al rendimiento deberíamos probar con varios valores por lo que aquí se ve la importancia de buscar objetivo, entonces elegimos las siguientes opciones en la cinta de Datos.

Luego configuramos los valores, ojo debe de estar establecida la fórmula para que realice los cálculos y pruebe los distintos resultados, de los contrario no funcionara.

Aceptamos y podemos apreciar que encontró el objetivo buscado, es decir para obtener un rendimiento de 17000 la tasa debe de ser de 14.17%

## Ejercicio 01

Llenar los siguientes datos, para tener las celdas formuladas. Y lo que se pide determinar es cuanto deberíamos de vender para obtener una utilidad neta de 450000

### 2.2. Actividad 2: Administrador de escenarios

Nos sirve para guardar distintos escenarios de cálculos sobre un proyecto. Abrimos el archivo proporcionado por el docente: **02 - Excel+Adm+de+Escenarios**

Como se puede apreciar ya tenemos todo calculado para el año 2020, en base a escenarios en uno pesimista crecerá al 9%, en uno conservador al 15% y en uno optimista al 22%, los gastos crecen solo el 3% para todos los años en todos los escenarios. En este caso igual que en el anterior ya debemos de tener las celdas formuladas.

Realizaremos el cálculo para el 2021 aquí debemos fijar la celda B19 para que no varie al momento de arrastrar la fórmula para los siguientes años y de allí corremos la formula par los siguientes años.

Ahora realizamos los mismo para Costos de Ventas para el 2021, pero tomando en consideración el 3% de gastos.

Arrastramos la fórmula para los siguientes años, tanto para Ventas como para Costo Ventas para los años 2022 y 2023.

Arrastramos la fórmula de utilidad bruta (celda B8) para los siguientes años.

Ahora calculamos los gastos administrativos, fijando la celda B20 como se aprecia en la figura.

Y arrastramos la fórmula para los siguientes años.

Ahora calculamos Gastos de Ventas para el 2021.

Arrastramos la fórmula para los siguientes años.

Arrastramos la fórmula de Utilidad Operativa para los siguientes años

Y lo mismo realizamos con los impuestos y utilidad neta simplemente arrastramos las fórmulas para los siguientes años.

Finalmente, calculamos el total de todas las ventas y lo etiquetamos con total Ventas como se aprecia en las imágenes.

Ahora configuraremos los escenarios, para lo cual vamos a las siguientes opciones de la cinta, elegimos **Datos** luego en **Análisis de hipótesis** luego **Administrador de escenarios** .

Si los escenarios ya aparecen como en la figura los eliminamos para agregarlos desde cero (para ello simplemente los seleccionamos uno a uno y presionamos eliminar).

En todo caso deberíamos partir desde lo siguiente:

Ahora si agregamos escenarios, en nombre de escenario escribimos **Pesimista** , en celdas cambiantes elegimos el valor de la celda B19 como se aprecia en la figura y a manera de comentario indicarle ventas al 9%.

Definimos el porcentaje e ingresamos 9% es decir 0.09 y presionamos aceptar.

Y de manera similar para los siguientes escenarios. en nombre de escenario escribimos **Conservador** , en celdas cambiantes elegimos el valor de la celda B19 como se aprecia en la figura y a manera de comentario indicarle ventas al 15%.

Definimos el porcentaje e ingresamos 9% es decir 0.15 y presionamos aceptar.

Y de manera similar para los siguientes escenarios. en nombre de escenario escribimos **Optimista** , en celdas cambiantes elegimos el valor de la celda B19 como se aprecia en la figura y a manera de comentario indicarle ventas al 22%.

Definimos el porcentaje e ingresamos 9% es decir 0.22 y presionamos aceptar.

Finalmente tendremos lo siguiente, todos los escenarios listos, seleccionamos el escenario que queremos ver y presionamos mostrar y allí veremos los cambios en Ventas Totales.

## Este es el escenario Conservador, podemos ver el Total de Ventas

Este es el escenario Optimista, podemos ver el Total de Ventas

## Ejercicio 02

Crear un escenario Pandemia donde el porcentaje de crecimiento sea del 85%, además proyectar los resultados aumentando 2 columnas a la tabla desarrollada, la del año 2024 y 2025.

### 2.3. Actividad 4: Consolidado

Un consolidado junta información de varias hojas de cálculo, en este caso abrimos el **archivo 03 - Excel+Consolidado.xlsx** , allí podemos apreciar la información de Alejandro, Ximena y Valeria los cuales tienen los mismos productos vendidos en los mismos meses, si quisiéramos consolidarlos seria sencillo, pero la desventaja es que si fueran demasiados productos (miles) y quisiéramos hacerlo manual será más tedioso.

Primero seleccionamos todos los productos de la Hoja Ventas de Alejandro, nos ubicamos en la cinta de opciones **Fórmulas** elegimos **Asignar nombre** y le asignamos un nombre.

Le asignamos un nombre, el resto de campos ya deberían de estar llenados automáticamente de lo contrario completar.

De la misma forma para Valeria y Ximena.

Ahora nos ubicamos en la hoja **Consolidado Primer Trimestre** y vamos a **Datos** luego a **Consolidar.**

Elegimos la operación sumar para obtener los totales, para esto usaremos los nombres que se les dio a las tablas de cada venta, elegimos en referencia a cada tabla como Alejandro y agregamos.

Como podemos apreciar al colocar el nombre Alejandro y presionar el botón Agregar nos mostrara la selección que habíamos nombrado antes, hacemos lo mismo para las demás tablas Valeria, Ximena y una vez que tengamos las tres presionamos aceptar, verifica que la función este en sumar y en Usar rótulo en, Columna izquierda y aceptamos.

Y acá ya le podemos dar formato para que sea más presentable o realizar operaciones como un total de ventas por mes, por ejemplo.

## Ejercicio 03

En una nueva hoja realizar el consolidado, pero con las ventas promedio (opción disponible en función de consolidado al igual que suma) de cada producto por mes.

### 2.4. **Tablas dinámicas:**

Abrimos el archivo de tablas dinámicas:

**04 - Excel+Tabla+dinamica+y+Filtros+Avanzados.xlsx**

Ubicamos el cursor en la celda G4 y seleccionamos la tabla. Luego elegimos la opción tabla dinámica, Asegúrate de seleccionar la tabla (solo donde estén los datos) incluyendo el nombre de las columnas y si no está seleccionado eliges Hoja de Calculo Existente

## Ahora observamos lo siguiente

Ahora quiero obtener las ventas totales por ubicación para ello arrastraremos el campo <mark>ventas</mark> a **Valores** y <mark>ubicación</mark> a **Filas**

Ahora quiero las ventas totales por producto, pero deseo que se filtre por ubicación. Para eso arrastramos <mark>ubicación</mark> a **filtros** , <mark>productos</mark> a **filas** y <mark>ventas</mark> a **valores** .

Ahora puedo filtrar por ubicación, en la lista desplegable que aparece en varios presionamos y seleccionamos algunas ubicaciones como se muestra y veremos que el calculo cambia.

## Verificamos

Ahora quiero saber a cuanto vendí cada producto, una forma es agregando el <mark>precio de producto</mark> a las **columnas** .

Podemos generar una imagen seleccionando toda la tabla dinámica y luego ir a la opción insertar imagen y elegir la sugerida por Excel

## Ejercicio 04

- a) Mostrar una tabla que me indique la cantidad de productos vendidos según su ubicación.

- b) Generar su grafico respectivo

## Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Ejercicio 01|04 puntos||
|Ejercicio 02|04 puntos||
|Ejercicio 03|04 puntos||
|Ejercicio 04a|04 puntos||
|Ejercicio 04b|04 puntos||
|**Total**|**20puntos**||

## Bibliografía

- <u>https://www.microsoft.com/es-es/microsoft-365/excel/spreadsheets</u>

- <u>https://support.microsoft.com/es-es/office/usar-buscar-objetivo-paraencontrar-el-resultado-que-desea-ajustando-un-valor-de-entrada-320cb99ef4a4-417f-b1c3-</u>

   - <u>4f369d6e66c7#:~:text=En%20la%20pesta%C3%B1a%20Datos%2C%20en,e l%20f%C3%B3rmula%20que%20desea%20resolver</u>

- <u>https://www.microsoft.com/es-es/microsoft-365/blog/2019/02/06/excel-withmicrosoft-excel-in-office-365/</u>
