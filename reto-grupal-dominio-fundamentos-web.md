# Reto Grupal - Dominio Fundamentos Web

## Introducción

En este proyecto vamos a desarrollar nuestra primera web colaborativa. Para ello crearemos una web con la información social de todos los miembros del equipo. De cara a nuestro CV online \(o LinkedIn\) **es muy importante dar visibilidad de que se ha ejecutado trabajo en equipo**. ¡Esta será la primera experiencia de trabajo en equipo relacionada con programación!



## Objetivos

1. Consolidar el aprendizaje de las tecnologías de Fundamentos Web \(HTML, CSS, diseño responsive, Flex, GitHub pages,  grid-layout\).
2. Utilizar control de versiones en equipo para aprender las ventajas y conflictos que genera.
3. Mejorar la comunicación de quienes son y cómo proyectan su trabajo como equipo.
4. Mejorar las habilidades de comunicación en público al exponer el proyecto en la sesión final.

## Caso de uso

Con esta web del equipo se podrá ilustrar este primer proyecto realizado en AG en su perfil de LinkedIn, añadiendo al resto de compañeros y el enlace al código en GitHub. De esta forma, las empresas podrán ver que durante el programa AG se ha adquirido experiencia de trabajo en equipo y podrán acceder fácilmente al código que se ha desarrollado.

## Especificaciones

Se desarrollará una página web con las siguientes características:

* Uso de HTML y CSS \(Puede usar cualquier marco de trabajo de CSS\)
* Uso de media-queries \(donde lo vea necesario implementar\) y otras técnicas de diseño _responsive_ para que la web se adapte al tamaño de pantalla de distintos dispositivos.
* Uso de git para el control de versiones del proyecto
* Publicación del resultado en Internet usando GitHub Pages

**La web tendrá varias páginas:**

* Página principal **\(**_**Home**_**\)** con la información principal sobre el equipo.
* Página de **contacto** con un formulario para que puedan ponerse en contacto con cada una de las integrantes.
* Opcionalmente, una página por cada componente del equipo con información más detallada sobre cada una.

Todas las páginas tendrán una cabecera **\(header\)** y un pie de página **\(footer\).** En la cabecera aparece el nombre del equipo y un menú de navegación que debe mantenerse fijo en la parte superior de la ventana al hacer **scroll**. En el pie de página aparece el **copyright**, otro menú **y una zona para ubicar un logo de su preferencia**.

**En la página principal, aparece:**

* una foto del equipo
* la frase representativa del equipo
* una sección "equipo" con la descripción del mismo \(que las identifica como equipo, cosas que tienen en común\), fortalezas y debilidades.
* una sección de "quiénes somos" con información resumida de cada miembro del equipo: nombre, foto, biografía breve y enlaces sociales \(Twitter, LinkedIn, GitHub y correo\)

**En la página de contacto** habrá un formulario que recoge información de contacto como nombre completo, email, teléfono y mensaje, y un botón para poder enviarlo \(aunque de momento no funcione\).

Las páginas principal y de contacto tienen un diseño establecido, al que debes ajustar lo máximo posible. El diseño está realizado para 3 tamaños de dispositivo

* **móvil, por debajo de 768px**
* **tablet, desde 768px hasta 1200px**
* **desktop, a partir de 1200px**

Para las páginas de cada componente del equipo, el diseño es libre pero siguiendo la guía de estilo del resto de la web.

### Logo, iconos tipografía y paleta

* El logo de su aplicación lo define cada equipo.
* Los iconos sociales se pueden obtener de [Font Awesome](https://fontawesome.com/), donde también pueden aprender cómo usarla.
* Las tipografías usadas en el diseño son Open Sans y Rubik, disponibles en Google Fonts.

### Colores

* Verde oscuro: \#099d8d
* Verde claro: \#14d9c4
* Blanco: \#ffffff
* Negro: \#000000
* Gris oscuro: \#54585a
* Gris claro: \#b8b8b9
* Gris de fondo: \#f1f1f1

### Zeplin

**Zeplin** es una aplicación para poder compartir un diseño con desarrolladores sin necesidad de que usen aplicaciones como Sketch, Illustrator o Photoshop, y con mucha más información que unos pantallazos.

Acá pueden ver un pequeño [tutorial en Youtube](https://www.youtube.com/watch?time_continue=12&v=tbKZAGthUgQ).

Se puede acceder al diseño directamente desde el navegador para ello se necesita una cuenta de zeplin \(que se puede conseguir de forma gratuita desde su página\).

URL del proyecto: [https://zpl.io/aXkApkx](https://zpl.io/aXkApkx)

## Hitos

Se les propone una serie de hitos como sugerencia para dividir las fases de este proyecto. Siguiendo los principios de las metodologías ágiles estableceremos pequeños ciclos iterativos de forma que al final de cada uno de estos generemos valor real, es decir, algo que nos beneficie y sea perceptible por nuestros usuarios \(los visitantes de la web\).

### Primero. Inicio del proyecto \(kickoff\)

* 1 sesión de trabajo 
* Organizar el trabajo a realizar usando Trello, e ir asignando tareas y responsables
* Establecer la organización del trabajo: qué tareas realizar en clase juntas y cuáles por separado en casa

### Segundo. Versión móvil de la web

* 4 sesiones de trabajo
* Desarrollar la versión para móvil de la web \(página principal y contacto, sin el formulario de momento\) con HTML y CSS
* Crear el contenido de la web: textos e imágenes
* Crear la infraestructura necesaria: repositorio en GitHub y con acceso para todos los miembros del equipo

> **NOTA**:  
> Para considerar terminado este hito y todos los siguientes se debe tener publicada la web en GitHub Pages.

### Tercero. Versión responsive de la web

* 2 sesiones de trabajo
* Hacer la web para el resto de tamaños de pantalla \(tablet, desktop\)

### Cuarto. Versión final

* 2 sesiones de trabajo
* Realizar el formulario de contacto para todos los dispositivos
* Aplicar las técnicas avanzadas aprendidas en la parte final del curso:
  * Grid en la sección de "quiénes somos"
  * Opcionalmente añadir animaciones y transiciones.

### Quinto. Presentación final

* 2 sesiones de trabajo
* El último día del sprint se presenta la versión final de este proyecto. Para ello se debe  dejarlo publicado y acabado con tiempo, y organizaros para realizar la presentación.

## Entrega

El formato de entrega de este proyecto será mediante la subida de este a la plataforma de GitHub. El nombre del repositorio deberá estar compuesto de las siguientes partes, todo ello separado por guiones:

* Nombre de la promoción : \(front2\)
* Nombre del equipo en minúsculas

Por ejemplo, el nombre de la primera promoción de AG fue "front1". Si un grupo realiza un proyecto y el nombre de ese grupo es "Lovelace", el nombre del repositorio debería ser "front1-lovelace".

Por último, para acompañar a la entrega del proyecto, el equipo realizará una presentación de 10 minutos mostrando la web y explicando los siguientes puntos:

* Cómo está estructurada la web y el contenido y el por qué de las decisiones tomadas.
* Cómo se ha seguido el diseño proporcionado.
* La estructura del código y las partes que se quieran destacar.
* Cómo ha sido la organización del equipo, el reparto de tareas y la coordinación a la hora de trabajar todas en el mismo código.
* Cuál de las tareas o los puntos ha sido el que más esfuerzo ha requerido.
* Cuál de las tareas o partes de la web es la que hace que el equipo esté más orgulloso.

Al final de esta presentación habrá un turno de preguntas tanto por parte de otras compañeras como por parte del profesor del curso.

## 



