## GUÍA DE LABORATORIO #02

### Tema

- Internet y herramientas colaborativas

### Competencias

- Herramientas de diagnóstico de red _ping_ , _ipconfig_ para evaluar la conectividad y analizar el comportamiento de las redes.

- Construcción de proyectos con Herramientas Colaborativas.

### Materiales/Herramientas

### Trabajo Preparatorio

- Es recomendable repasar los conceptos teóricos vistos en clase antes de comenzar la práctica

# Fundamento teórico

- 1.1. **¿Qué es Internet?**

Internet, la "red de redes", es un sistema global que conecta dispositivos a través del protocolo TCP/IP. Esta interconexión masiva permite la comunicación y el intercambio de información a escala planetaria, convirtiéndola en una plataforma fundamental para la sociedad actual.

### <u>Ping</u>

Es una instrucción de linea de comandos (instrucción de consola) que envía paquetes de datos ICMP (Protocolo de Mensajes de Control de Internet) a un destino específico y mide el tiempo de respuesta. Esto permite verificar si un dispositivo en la red está activo y accesible.

### ¿Qué son los paquetes de datos ICMP?

Imagina que Internet es como un sistema postal gigante. Las cartas que enviamos por correo son como _paquetes de datos_ . Estos paquetes contienen toda la información que queremos enviar, como un mensaje, una imagen o un video. Los paquetes ICMP son como los carteros que llevan estas cartas. Pero en lugar de entregar cartas de verdad, los paquetes ICMP llevan mensajes especiales que dicen cosas como: "¡Tu carta llegó!", "¡No puedo encontrar la dirección!", o "¡Hay un atasco en el camino!".

### ● **¿Por qué son importantes los paquetes ICMP?**

### <u>Ipconfig</u>

Muestra la configuración de red (interfaz de red) utilizando el modelo TCP/IP. Es una herramienta útil para obtener información detallada sobre la conexión de red de un equipo. Al ejecutar el comando _ipconfig_ , se muestra una lista de adaptadores de red y sus respectivas configuraciones, esto incluye:

**Dirección IP:** La dirección única que identifica al equipo en la red. **Máscara de subred:** Define el rango de direcciones IP que pertenecen a la misma red.

**Puerta de enlace predeterminada:** El dispositivo que dirige el tráfico de red fuera de la red local.

**Servidores DNS:** Los servidores que traducen nombres de dominio a direcciones IP.

- **¿Para qué se utiliza ipconfig?**

### 1.2. **¿Qué es DNS?**

Imagina que quieres visitar tu sitio web favorito. En lugar de tener que recordar una larga secuencia de números ( _dirección IP_ ), simplemente escribes el nombre del sitio o _nombre de dominio_ , por ejemplo <u>www.unsaac.edu.pe</u> en la barra de direcciones de tu navegador, pero **¿cómo hace tu navegador para encontrar este sitio web?**

Aquí es donde entra en juego el Sistema de Nombres de Dominio (DNS). El DNS es como una guía telefónica gigante de Internet. Convierte los nombres de dominio fáciles de recordar <u>(www.unsaac.edu.pe)</u> en direcciones IP numéricas que las computadoras utilizan para comunicarse.

**Figura 01** : Proceso en el cual se cambia un nombre de dominio por una dirección IP. Fuente: Elaboración propia

### 1.3. **Ambientes virtuales y herramientas colaborativas**

### ¿Qué son herramientas colaborativas?

Herramientas colaborativas son aplicaciones o plataformas digitales diseñadas para facilitar el trabajo en equipo, permitiendo a los usuarios compartir recursos, comunicarse en tiempo real, gestionar proyectos y colaborar en la creación de contenido, sin necesidad de estar físicamente en el mismo lugar.

### Sus características principales son:

- ✔ Sincronización en Tiempo Real

- ✔ Acceso Remoto

- ✔ Comunicación Integrada

- ✔ Gestión de Tareas

Herramientas colaborativas son aplicaciones o plataformas digitales diseñadas para facilitar el trabajo en equipo, permitiendo a los usuarios compartir recursos, comunicarse en tiempo real, gestionar proyectos y colaborar en la creación de contenido, sin necesidad de estar físicamente en el mismo lugar.

### ¿Qué aplicaciones en la Educación y el Trabajo tiene?

- **En la Educación:** Colaboración en grupo, compartir recursos y comunicación entre estudiantes y profesores de manera eficiente.

- **En el Trabajo Remoto:** Permiten a los equipos de trabajo coordinarse, compartir información y mantenerse conectados, independientemente de su ubicación geográfica.

### ¿Qué son Ambientes Virtuales?

Son entornos simulados que se crean mediante software, permitiendo a los usuarios _interactuar_ con un _espacio digital_ que emula características de un ambiente físico. Estos ambientes son utilizados para diferentes propósitos, como la educación, el entretenimiento, la simulación de situaciones reales y el trabajo colaborativo.

### Sus características principales son:

- ✔ Sincronización en Tiempo Real

- ✔ Acceso Remoto

- ✔ Comunicación Integrada

- ✔ Gestión de Tareas

### ¿Qué aplicaciones en la Educación y el Trabajo tiene?

- **En la Educación:** Permiten la creación de aulas virtuales, donde los estudiantes pueden participar en actividades, discusiones y simulaciones.

- **En el Trabajo Remoto:** Empresas y organizaciones utilizan ambientes virtuales para reuniones, entrenamientos y colaboraciones a distancia.

# Aplicación de la guía

- 2.1. **Actividad 1: Uso de ipconfig y ping. Obtener información de la configuración de red.**

- Abre una terminal de comandos. Ejecuta el comando **ipconfig** identifica los siguientes elementos:

**Figura 02** : Consola de Windows mostrando la configuración de Red (comando: _ipconfig /all_ ). Fuente: Elaboración propia

- Dirección IP: _

- Máscara de subred: __

- Puerta de enlace predeterminada: ___

- Servidor DNS: _

### _Ejecución del comando ping_

- Abre una nueva ventana de terminal. Ejecuta el comando **ping 200.48.82.6**

- Repite este proceso para los siguientes dominios: _google.com_ y _facebook.com_

- 2.2. **Actividad 2 (Propuesta):** Trabajando en grupo y utilizando una herramienta colaborativa en la nube (Mind Meister o Canva) elabora un Mapa Mental que describa los conceptos más importantes aprendidos en esta guía.

### 2.3. Actividad 3 (Propuesta): Diseño y Publicación de un Blog o Página Web Institucional de forma colaborativa

Trabajando en grupo construir un Blog o página web utilizando la herramienta de Google Sites desde sus cuentas institucionales de manera colaborativa. Para crear un Sitio Web en la nube, sigue los siguientes pasos

- Dentro de _Google Drive_ , buscar el botón “ _Nuevo_ ”

- Hacer clic en el botón “ _Nuevo_ ”,

- luego clic en _más_ ,

- luego en “ _Sitios de Google_ ”, como se muestra en la imagen a continuación:

En la pantalla podrás visualizar la plantilla de un sitio web simple, la cual puedes personalizar usando los siguientes elementos ( _Figura 02_ ):

**1.** Aquí coloca el título de tu sitio web, ejemplo: miweb.com

**2.** Aquí se encuentra el panel de controles, dichos controles te ayudarán a editar tu sitio web, puedes colocar texto, importar una imagen e incluso adicionar fragmentos de código HTML.

**3.** Este es el panel principal de tu sitio web, aquí se muestran todos los elementos que vayas insertando.

**4.** Finalmente, una vez que termines de editar tu sitio puedes publicarlo en Internet haciendo clic en el botón “ _Publicar_ ”, aquí colocar un nombre a tu web. Podrás obtener una URL para que cualquiera pueda acceder a tu web, la _Figura 02_ muestra cada uno de estos pasos descritos.

**Figura 03** : Pasos para configurar una página web creada con Google Sites. Fuente: Elaboración propia

### Ahora, crear tu propio sitio web de manera colaborativa

- En grupos creen un sitio web con imágenes de cada miembro.

- Cada uno coloque su nombre y una breve descripción.

- La _Figura 04_ muestra un ejemplo de como pueden estructurar su página.

- Publícalo en Internet.

- Muestra al profesor el URL.

**Figura 04** : Página después de aplicar “BLOQUES DE CONTENIDO”.

Fuente: Elaboración propia

### Evaluación

|**Criterio**|**Puntaje máximo**|**Puntaje obtenido**|
|---|---|---|
|Actividad 1|05 puntos||
|Actividad 2|08 puntos||
|Actividad 3|07 puntos||
|**Total**|**20 puntos**||

### Bibliografía

- Tanenbaum, A. S., & Wetherall, D. J. (2012). Redes de computadoras Quinta Edicion.

- Google Slides, 27 Agosto 2024, [https://sites.google.com]

- Google Workspace, 27 Agosto 2024, [https://workspace.google.com/features]

- Teeter, R., & Barksdale, K. (2009). Google Sites and Chrome for dummies. John Wiley & Sons.

- Zimmerman, J., & Ng, D. (2015). Social media marketing all-in-one for dummies. John Wiley & Sons.
