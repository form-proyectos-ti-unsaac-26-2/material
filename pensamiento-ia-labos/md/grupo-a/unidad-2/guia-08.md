# GUÍA DE LABORATORIO N° 8

## Tema

## ● **Gestión y visualización de datos Competencias**

- Comprender los conceptos básicos de gestión y visualización de datos en el contexto de la ingeniería.

- Manejar herramientas de Power BI para la creación de dashboards interactivos en ingeniería.

- Analizar y extraer información relevante para crear soluciones basadas en ingeniería utilizando Power BI.

- Desarrollar habilidades para la toma de decisiones basadas en datos visualizados.

## Materiales/Herramientas

- Microsoft Power BI Desktop

- Conjunto de datos de ejemplo relacionado con ingeniería (puede ser un archivo Excel o CSV).

- Conexión a Internet para acceder a recursos adicionales y tutoriales en línea.

## Fundamento teórico

### 1.1. Power BI

Power BI permite la integración de grandes volúmenes de datos provenientes de diferentes fuentes, lo que es esencial en proyectos de ingeniería donde se recopilan datos de sensores, bases de datos, hojas de cálculo, y más.

La gestión de datos en Power BI incluye la conexión a bases de datos clínicas, la limpieza y transformación de datos para que sean útiles en análisis, y la creación de visualizaciones que faciliten la interpretación de estos datos. Las visualizaciones pueden ayudar a identificar patrones, comparar resultados, y mejorar la calidad de la atención médica.

La versión de escritorio se puede descargar de: <u>https://www.microsoft.com/es-es/download/details.aspx?id=58494</u>

#### 1.1.1. Características de Power BI

- **Conexión a múltiples fuentes de datos:** como bases de datos SQL, archivos Excel, servicios en la nube, etc.

- **Transformación de datos:** utilizando el editor de consultas, que permite filtrar, agrupar, y modificar los datos.

- **Visualización:** creación de gráficos interactivos como barras, líneas, mapas, etc.

- **Dashboards:** un tablero interactivo que permite combinar múltiples visualizaciones y resúmenes de datos.

#### 1.1.2. Partes de Power BI

- (1) La cinta en la parte superior, en la que se muestran las tareas comunes asociadas con los informes y las visualizaciones.

- (2) El área de lienzo del centro, donde se pueden crear y organizar las visualizaciones.

- (3) El área de pestañas de página en la parte inferior, que permite seleccionar o agregar páginas del informe.

- (4) El panel Filtros, donde puede filtrar las visualizaciones de datos.

- (5) El panel Visualizaciones, donde puede agregar, cambiar o personalizar visualizaciones, y aplicar la obtención de detalles.

- (6) El panel Formato, donde se diseñan el informe y las visualizaciones.

- (7) El panel Campos, donde se muestran los campos disponibles en las consultas. Puede arrastrar estos campos al lienzo, el panel Filtros o el panel Visualizaciones para crear o modificar visualizaciones.

Figura 1 Partes de la interfaz de PowerBI

Fuente: <u>https://learn.microsoft.com/es-es/power-bi/fundamentals/desktop-getting-started</u>

#### 1.1.3. Tipos de visualizaciones de Power BI

- Gráficos de áreas: básico (en capa) y de área apilada

- Gráficos de barras y columnas

- Cards

- Número único

- Gráficos combinados

- Esquema jerárquico

- Gráficos de anillos

- Gráficos de embudo

- Gráficos de medidor

- Gráfico de influenciadores clave

- KPI

- Gráficos de líneas

- Maps

- Matriz

- Gráficos circulares

- Dispersión

- Segmentaciones

- Tablas

- Gráficos de rectángulos

- Gráficos de cascada

## Aplicación de la guía

### 2.1. Actividad 1: Creación de un dashboard interactivo

**Paso 1:** Descargar el Conjunto de Datos: <u>https://www.datosabiertos.gob.pe/dataset/proyectos-financiados-enejecuci%C3%B3n-de-proinnovate-programa-nacional-de-desarrollo</u>

- Visita el enlace proporcionado: Listado de los proyectos financiados en ejecución del programa ProInnovate.

- Haz clic en el botón de **“Descargar”** para obtener el archivo en formato CSV o Excel.

**Paso 2:** Cargar el Conjunto de Datos en Power BI

- Abre Power BI Desktop.

- Selecciona la opción **"Obtener datos"** y elige **"CSV"** (o el formato adecuado del archivo descargado).

- Navega hasta el archivo descargado y selecciónalo.

- En el panel de importación, selecciona la hoja o tabla que contiene los datos y haz clic en **"Cargar"** .

**Paso 3:** Transformar y Limpiar los Datos

- Seleccionar en **"Origen de archivo"** la opción **65001:Unicode (UTF-8)** , para reconocer la letra “ñ” y tildes.

- Una vez cargados los datos, selecciona **"Transformar datos"** para abrir el Editor de Power Query.

- Revisa el conjunto de datos para identificar posibles columnas irrelevantes o inconsistentes.

- Realiza y/o revisa las siguientes posibles transformaciones comunes:

   - Cambiar tipo (Por ejemplo convertir los enteros en fechas )

   - Elimina columnas que no sean necesarias. (Por ejemplo probar con campos _null_ )

   - Corrige errores de datos, como nombres de edades mal escritos o celdas en blanco.

   - Cambia el tipo de datos de columnas como fechas o números.

   - Filtra los datos para mantener solo los años y regiones relevantes.

- Haz clic en **"Cerrar y aplicar"** para guardar las transformaciones.

**Paso 4:** Crear Visualizaciones en Power BI

En la vista de informe de Power BI, selecciona "Visualizaciones" y elige los tipos de visualizaciones adecuadas (gráficos de barras, líneas, mapas, etc.) para representar los datos de manera clara y efectiva.

Crea las siguientes visualizaciones:

- Gráfico de columnas agrupadas. (Arrastrar AÑO a Eje X, y MONTO_FINANCIERO a Valores)

- Gráfico circular de MONTO_FINANCIERO po FONDO. (Cambiar a recuento)

- Mapa geográfico para mostrar la distribución de los MONTO_FINANCIERO. (Arrastrar DEPARTAMENTO a Ubicación)

- Gráfico de líneas de evolución de FONDO en el tiempo (FECHO_INICIO).

Arrastra y suelta los campos desde el panel de Campos a las visualizaciones que estás creando.

**Paso 5:** Publicar y Compartir el Dashboard

- Guarda el archivo de Power BI.

### 2.2. Actividad 2: Análisis de Datos con Insights (Conclusiones)

**Paso 1:** Descargar y Cargar el Conjunto de Datos

- Utilizaremos el mismo conjunto de datos de la actividad 1.

- Cargar el conjunto de datos en Power BI:

- Abre Power BI Desktop.

- Selecciona **"Obtener datos"** y elige el formato de archivo correspondiente (Excel o CSV).

- Carga el archivo descargado y asegúrate de seleccionar la hoja o tabla correcta que contiene los datos.

**Paso 2:** Explorar y Entender los Datos

- Explorar el contenido del conjunto de datos:

- Observa las columnas disponibles (como fechas, datos geográficos, montos, etc.).

- Familiarízate con el tipo de datos (numéricos, categóricos, fechas).

Identificar preguntas claves para el análisis:

- ¿Cuál es la provincia con más proyectos?

- ¿Cuáles son los contratos con más aportes de recurso no reembolsable?

- ¿Cómo varía el monto no financiero en el tiempo?

- ¿Existen patrones estacionales o geográficos en los datos?

**Paso 3:** Transformar y Preparar los Datos

- Limpiar y transformar los datos en el Editor de Power Query:

- Elimina filas vacías o datos irrelevantes.

- Corrige errores en los datos (por ejemplo, celdas con entradas incorrectas).

- Convierte las columnas a su tipo de datos adecuado (fechas, números, texto).

- Agrega columnas calculadas si es necesario.

## **Paso 4:** Visualizar los Datos

Crear visualizaciones preliminares.

**Paso 5:** Analizar Insights Relevantes

- Buscar patrones y tendencias:

   - Observa la tendencia general de los montos en el tiempo. ¿Están aumentando o disminuyendo?

   - Identifica las provincias con montos reducidos. ¿Existe un patrón claro en la distribución de los montos?

- Investigar anomalías o variaciones:

   - Identifica cualquier anomalía o pico inusual en los datos.

   - Explora posibles razones detrás de esas anomalías.

**Paso 6:** Presentar los Insights

- Crear un informe narrativo en Power BI:

- Agrega páginas al informe en Power BI para organizar las visualizaciones por tema (tendencias temporales, comparación por edad, etc.).

- Inserta cuadros de texto para explicar los insights encontrados y proporcionar contexto.

- Personalizar el diseño del informe:

   - Ajusta colores, fuentes, y estilos para que el informe sea visualmente atractivo y fácil de entender.

   - Asegúrate de que todas las visualizaciones tengan títulos claros, leyendas y etiquetas.

**Paso 7:** Compartir el Informe y Facilitar la Discusión

- Publicar el informe en Power BI Service:

- Guarda y publica el informe en Power BI Service para compartirlo con los estudiantes o partes interesadas.

- Facilitar una discusión basada en los insights:

- Organiza una sesión de discusión donde los estudiantes presentan sus hallazgos y recomendaciones.

### 2.3. Actividad 3 (Propuesta): Resuelve el ejercicio

Similar a la actividad 1, Realiza un dashboard con datos obtenidos del siguiente dataset:

<u>https://www.datosabiertos.gob.pe/dataset/proyectos-reactiva-per%C3%BA</u>

Agrega al menos 5 tipos de visualizaciones coherentes.

Comparte el dashboard con el docente. Asegúrate de que el dashboard sea fácil de entender.

Añade títulos, etiquetas y leyendas donde sea necesario.

Revisa el dashboard para asegurarte de que todas las visualizaciones sean precisas y estén bien presentadas.

## Ejercicios adicionales:

Utilizando el mismo dataset de la actividad 3, identifica y analiza insights relevantes del dataset y presenta los hallazgos en un informe narrativo utilizando Power BI. Analiza los datos para responder las siguientes preguntas clave:

- ¿Cuál es el ámbito con más monto de inversión y transferencia?

- ¿Cuáles son las regiones con más empleos?

- ¿Existe una correlación entre el monto de inversión y la beneficiaria?

- ¿Qué unidad ejecutora posee más proyectos en ejecución?

- ¿Cómo varía el monto de inversión por región?

- Identifica cualquier anomalía o patrón inusual en los datos.

## Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|06 puntos||
|Actividad 2|06 puntos||
|Actividad 3|08 puntos||
|**Total**|**20puntos**||

## Bibliografía

- Chandra, G. (2020). _Mastering Power BI: A comprehensive guide to building, deploying, and managing data analytics dashboards._ Packt Publishing.

- Ferrer, M. (2021). _Power BI: Una guía completa para principiantes._ Editorial Albahaca.

- _Martínez, A. (2019). Visualización de datos en proyectos de ingeniería: Estrategias y mejores prácticas._ Revista de Tecnología y Gestión, 38(1), 5672.

- Microsoft. (2023). _Power BI Documentation_ . Recuperado de <u>https://docs.microsoft.com/en-us/power-bi/</u>
