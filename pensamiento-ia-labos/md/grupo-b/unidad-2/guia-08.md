# GUÍA DE LABORATORIO #08

## Tema

## ● **Gestión y visualización de datos Competencias**

- Comprender los conceptos básicos de gestión y visualización de datos en el contexto de la salud.

- Manejar herramientas de Power BI para la creación de dashboards interactivos en ciencias de la salud.

- Analizar y extraer información relevante para la salud pública y la gestión hospitalaria utilizando Power BI.

- Desarrollar habilidades para la toma de decisiones clínicas basadas en datos visualizados.

## Materiales/Herramientas

- Microsoft Power BI Desktop

- Conjunto de datos de ejemplo relacionado con salud (puede ser un archivo Excel o CSV con datos de pacientes, estadísticas de salud pública, etc.).

- Conexión a Internet para acceder a recursos adicionales y tutoriales en línea.

## Fundamento teórico

### 1.1. Power BI

Power BI es una herramienta de Business Intelligence (BI) que permite a los profesionales de la salud analizar grandes volúmenes de datos y visualizarlos de manera que puedan tomar decisiones informadas. En el ámbito de la salud, Power BI se utiliza para analizar datos de pacientes, resultados clínicos, tendencias en salud pública, y la gestión de recursos hospitalarios.

La gestión de datos en Power BI incluye la conexión a bases de datos clínicas, la limpieza y transformación de datos para que sean útiles en análisis, y la creación de visualizaciones que faciliten la interpretación de estos datos. Las visualizaciones pueden ayudar a identificar patrones, comparar resultados, y mejorar la calidad de la atención médica. La versión de escritorio se puede descargar de:

<u>https://www.microsoft.com/es-es/download/details.aspx?id=58494</u>

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

Figura 1 Partes de la interfaz de PowerBI Fuente: <u>https://learn.microsoft.com/es-es/power-bi/fundamentals/desktop-getting-started</u>

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

**Paso 1:** Descargar el Conjunto de Datos: <u>https://www.datosabiertos.gob.pe/dataset/casos-de-anemia-por-edades-entrelos-a%C3%B1os-2010-2020-en-la-region-de-cusco</u>

Visita el enlace proporcionado: Casos de Anemia por Edades entre 2010-2020 en la Región de Cusco.

Haz clic en el botón de descarga para obtener el archivo en formato CSV o Excel.

**Paso 2:** Cargar el Conjunto de Datos en Power BI

Abre Power BI Desktop.

Selecciona la opción "Obtener datos" y elige "CSV" (o el formato adecuado del archivo descargado).

Navega hasta el archivo descargado y selecciónalo.

En el panel de importación, selecciona la hoja o tabla que contiene los datos y haz clic en "Cargar".

**Paso 3:** Transformar y Limpiar los Datos

Una vez cargados los datos, selecciona "Transformar datos" para abrir el Editor de Power Query.

Revisa el conjunto de datos para identificar posibles columnas irrelevantes o inconsistentes.

Realiza y/o revisa las siguientes posibles transformaciones comunes:

Elimina columnas que no sean necesarias. (Por ejemplo probar con Red)

Corrige errores de datos, como nombres de edades mal escritos o celdas en blanco.

Cambia el tipo de datos de columnas como fechas o números.

Filtra los datos para mantener solo los años y regiones relevantes.

Haz clic en "Cerrar y aplicar" para guardar las transformaciones.

**Paso 4:** Crear Visualizaciones en Power BI

En la vista de informe de Power BI, selecciona "Visualizaciones" y elige los tipos de visualizaciones adecuadas (gráficos de barras, líneas, mapas, etc.) para representar los datos de manera clara y efectiva.

Crea las siguientes visualizaciones:

- Gráfico de líneas para mostrar la tendencia de casos de anemia a lo largo de los años. (Arrastrar AÑO a Eje X, y CASOS a Eje Y)

- Gráfico de barras para comparar los casos de anemia por diferentes grupos de edad. (Arrastrar EDAD a Eje X, y CASOS a Eje Y)

- Mapa geográfico para mostrar la distribución de los casos en la región de Cusco. (Arrastrar DISTRITO a Ubicación)

- Tarjetas de KPI para mostrar métricas clave como el número total de casos de anemia. (Arrastar CASOS a Campos)

Arrastra y suelta los campos desde el panel de Campos a las visualizaciones que estás creando.

**Paso 5:** Publicar y Compartir el Dashboard

Guarda el archivo de Power BI.

Haz clic en "Publicar" en la cinta de opciones para subir el dashboard a Power BI Service (requiere cuenta en Power BI).

Comparte el enlace con los estudiantes o interesados para que puedan interactuar con el dashboard en línea.

### 2.2. Actividad 2: Análisis de Datos de Salud Pública con Insights

**Paso 1:** Descargar y Cargar el Conjunto de Datos

Utilizaremos el mismo conjunto de datos de la actividad 1.

Cargar el conjunto de datos en Power BI:

Abre Power BI Desktop.

Selecciona "Obtener datos" y elige el formato de archivo correspondiente (Excel o CSV).

Carga el archivo descargado y asegúrate de seleccionar la hoja o tabla correcta que contiene los datos.

**Paso 2:** Explorar y Entender los Datos

Explorar el contenido del conjunto de datos:

Observa las columnas disponibles (como Año, Edad, Región, Casos de Anemia, Severidad, etc.).

Familiarízate con el tipo de datos (numéricos, categóricos, fechas).

Identificar preguntas claves para el análisis:

- ¿Cuál es la tendencia de los casos de anemia a lo largo del tiempo?

- ¿Qué grupo de edad es más afectado por la anemia?

- ¿Cómo varía la severidad de los casos por edad o año?

- ¿Existen patrones estacionales o geográficos en los datos?

**Paso 3:** Transformar y Preparar los Datos

Limpiar y transformar los datos en el Editor de Power Query:

Elimina filas vacías o datos irrelevantes.

Corrige errores en los datos (por ejemplo, celdas con entradas incorrectas).

Convierte las columnas a su tipo de datos adecuado (fechas, números, texto).

Agrupa los datos si es necesario, como sumar casos de anemia por año o por grupo de edad.

Crear columnas calculadas:

Agrega columnas calculadas si es necesario, como el porcentaje de casos de anemia por grupo de edad o la tasa de crecimiento anual de los casos.

**Paso 4:** Visualizar los Datos

Crear visualizaciones preliminares:

- Utiliza gráficos de líneas para visualizar la tendencia temporal de los casos de anemia.

- Crea gráficos de barras o columnas para comparar la prevalencia de anemia entre diferentes grupos de edad.

- Utiliza gráficos de dispersión para analizar la relación entre diferentes variables, como la severidad y la edad.

**Paso 5:** Analizar Insights Relevantes

Buscar patrones y tendencias:

Observa la tendencia general de los casos de anemia a lo largo de los años. ¿Están aumentando o disminuyendo?

Identifica los grupos de edad más afectados. ¿Existe un patrón claro en la distribución de casos por edad?

Investigar anomalías o variaciones:

Identifica cualquier anomalía o pico inusual en los datos (por ejemplo, un aumento repentino en un año específico).

Explora posibles razones detrás de esas anomalías (cambios en políticas de salud, eventos socioeconómicos, etc.).

Extraer insights significativos:

Formula conclusiones sobre las áreas que necesitan atención o intervención en salud pública.

Propón recomendaciones basadas en los datos, como estrategias de prevención o tratamiento focalizadas en grupos vulnerables.

**Paso 6:** Presentar los Insights

Crear un informe narrativo en Power BI:

Agrega páginas al informe en Power BI para organizar las visualizaciones por tema (tendencias temporales, comparación por edad, etc.).

Inserta cuadros de texto para explicar los insights encontrados y proporcionar contexto.

Personalizar el diseño del informe:

Ajusta colores, fuentes, y estilos para que el informe sea visualmente atractivo y fácil de entender.

Asegúrate de que todas las visualizaciones tengan títulos claros, leyendas y etiquetas.

**Paso 7:** Compartir el Informe y Facilitar la Discusión

Publicar el informe en Power BI Service:

Guarda y publica el informe en Power BI Service para compartirlo con los estudiantes o partes interesadas.

Facilitar una discusión basada en los insights:

Organiza una sesión de discusión donde los estudiantes presentan sus hallazgos y recomendaciones.

Fomenta el debate sobre cómo los datos pueden guiar decisiones en salud pública, como políticas de prevención o distribución de recursos.

### 2.3. Actividad 3 (Propuesta): Resuelve el ejercicio

Similar a la actividad 1, Realiza un dashboard con datos obtenidos del siguiente dataset: “Peru COVID-19”

<u>https://www.kaggle.com/datasets/martinclark/peru-covid19-august-2020</u>

Agrega al menos 5 tipos de visualizaciones coherentes.

Comparte el dashboard con el docente.

Asegúrate de que el dashboard sea fácil de entender. Añade títulos, etiquetas y leyendas donde sea necesario.

Revisa el dashboard para asegurarte de que todas las visualizaciones sean precisas y estén bien presentadas.

### 2.4. Ejercicios adicionales

Utilizando el mismo dataset de la actividad 3, identifica y analiza insights relevantes del dataset y presenta los hallazgos en un informe narrativo utilizando Power BI. Analiza los datos para responder las siguientes preguntas clave:

- ¿Cuál es la tendencia de nuevos casos y muertes diarias durante agosto de 2020?

- ¿Cuáles son las regiones más afectadas en términos de casos y muertes?

- ¿Existe una correlación entre el número de pruebas realizadas y los casos confirmados?

- ¿Qué días de la semana presentaron un mayor número de contagios y fallecimientos?

- ¿Cómo varía la tasa de mortalidad por región?

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

- Heger, O. (2022). _Data Science in Healthcare: Practical applications and case studies._ Springer.

- Microsoft. (2023). _Power BI Documentation_ . Recuperado de <u>https://docs.microsoft.com/en-us/power-bi/</u>
