# Introducción a HTML

HTML es el acrónimo de "HyperText Markup Language". HTML es un lenguaje de marcas de hipertexto, permitiendo que se pueda definir la estructura de una página web.

HTML está basado en etiquetas, las etiquetas son el elemento fundamental en HTML. Una etiqueta es una palabra que se encuentra encerrada por un signo de menor que`<` y un signo de mayor que `>` .

La gran mayoría de las etiquetas HTML necesitan una etiqueta de cierre donde al querer cerrar nuestra etiqueta se agrega un signo de división o slash `/` antes de la palabra de la etiqueta.

Por ejemplo para querer mostrar un párrafo hacemos uso de la etiqueta `<p>` y de su correspondiente etiqueta de cierre `</p>` , en el medio de estas dos etiquetas iría el contenido del párrafo que deseamos agregar:

```markup
<p>Bienvenido al curso Frontend de la academia geek =D</p>
```

### Mi documento HTML

Un documento HTML es aquel que posee la extensión `.html` donde vamos a poder colocar todo nuestro código HTML, la estructura básica de un documento HTML sería la siguiente:

{% code title="mi-primer-documento.html" %}
```markup
<!DOCTYPE html>
<html>
    <head>
        <title> Academia Geek </title>
    </head>
    <body>
        <h1> Bienvenido a nuestra Academia! </h1>
        <p> Ya eres parte de nuestra comunidad Geek </p>
    </body>
</html>
```
{% endcode %}

Nuestros documentos HTML debe iniciar con `<!DOCTYPE html>` con esta etiqueta le estamos indicando que vamos a trabajar con la última versión de HTML, HTML 5, la cual nos permite usar etiquetas que mejoran la semántica web.

### Etiquetas de texto

Es importante que todo el contenido a crear en nuestro sitio web este dentro de etiquetas, lo cual esta orientado a que usemos buenas prácticas al crear nuestras estructuras HTML

### Etiquetas Esenciales

_**head**_

Dentro de esta etiqueta se colocan elementos que el navegador va a usar para pero no se van a mostrar en el cuerpo de la página. Aqui van elementos como el título de nuestra página, la imagen que aparece en la pestaña del navegador, o las palabras clave para indexar en buscadores.

_**body**_

Todos los elementos que se escriban dentro de esta etiqueta se van a mostrar en nuestro sitio web. Aquí van las etiquetas de texto, imágenes, botones, inputs, 

_**title**_

Muestra el texto introducido entre las etiquetas de apertura y cierre, en la pestaña del navegador.

### Etiquetas comunes

#### Párrafos

Los párrafos se definen con la etiqueta `<p>`:

```markup
<p>Soy desarrollador FrontEnd</p>
<p>Me preparé en la academia Geek</p>
```

#### Títulos \(encabezados\)

Los títulos se definen con las etiquetas `<h1>` a `<h6>` siendo `<h1>` el título de mayor relevancia e importancia y `<h6>` el de menos importancia:

```markup
<h1>Mi portafolio</h1>
<h2>Mis Proyectos</h2>
<h3>Tienda Virtual</h3>
```

#### Enlaces \(links\)

Los vínculos se definen con la etiqueta `<a>`:

```markup
<a href="http://academiageek.co/">Academia Geek</a>
```

El destino del vínculo se define en el **atributo** `href`. Los atributos se utilizan para proveer información adicional a la etiqueta.

#### Imágenes

Las imágenes se definen con la etiqueta `<img>`:

```markup
<img src="logo-academia-geek.jpg" alt="Nuestro logo">
```

La etiqueta `<img>` **no** es necesario que posean una etiqueta de cierre. El atributo `src` contiene la ruta en donde se encuentra nuestra imagen y el atributo `alt` contiene el texto que describe la imagen.

#### **Listas**

Son estructuras que definen una lista, pueden ser ordenadas `ol` o desordenadas `ul`. las listas contienen items de lista.

```markup
<ul>
    <li>item de lista</li>
    <li>item de lista</li>
</ul>
```

### Comentarios

Podemos agregar comentarios al código HTML utilizando la siguiente sintaxis:

```markup
<!-- En esta sección vamos a ver un contenido genial -->
```



