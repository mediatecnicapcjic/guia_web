# Terminal de comándos

La **línea de comandos** \(también conocida como consola, terminal o símbolo del sistema\) era la única forma de interactuar con un computador antes que aparecieran las interfaces gráficas.

La **línea de comandos** es una aplicación en la que puedes escribir y ejecutar comandos para realizar tareas como:

* Navegar por las carpetas de tu computador.
* Manipular archivos \(crear, editar, copiar, mover y eliminar\).
* Conectarte a servidores remotos.
* Crear **scripts** que te ayuden con tus tareas diarias.

## Primer comando: la ubicación actual

En la **línea de comandos** siempre vas a estar ubicado\(a\) sobre una ruta \(carpeta\) de tu sistema.

Para conocer la ruta actual puedes escribir el comando `pwd` y oprimir `Enter`.

**Nota:** No olvides el `Enter` al final de cada comando para ejecutarlo!

Por ejemplo, en mi **línea de comandos** \(la que ves en la imagen arriba\) se ve así:

```text
Last login: Wed Feb 24 20:10:39 on ttys001
~$ pwd
/Users/germanescobar
~$
```

Cada vez que escribes un comando aparece el resultado debajo y nuevamente el `prompt`.

**Nota:** De ahora en adelante vamos a representar el `prompt` con el símbolo `$`. Ese símbolo **no** lo tienes que escribir en tu **línea de comandos**.

## Listando carpetas y archivos

Para listar las carpetas y los archivos de la ubicación actual vas a utilizar el comando `ls`:

```text
$ ls
```

La forma en que este comando muestra los resultados varía dependiendo de la **línea de comandos** y la configuración. 

## Cambiando de ubicación

Para cambiar de carpeta en la **línea de comandos** utilizas el comando `cd` seguido de la ruta de la carpeta. Por ejemplo, si quieres ir a la carpeta raíz de tu sistema debes escribir:

```text
$ cd /
```

### Rutas relativas y absolutas

Para las rutas de las carpetas puedes utilizar rutas relativas o absolutas.

Una **ruta relativa** toma como referencia la carpeta actual.

Una **ruta absoluta** inicia con `/` y se refiere a la ruta completa desde la carpeta raíz de tu sistema.

Por ejemplo, si nos encontramos en la carpeta `/Users/johnflorez`, la **ruta relativa** `Projects/images` se refiere a la **ruta absoluta** `/Users/johnflorez/Projects/images`.

### La carpeta del usuario

Cuando ingresas a la **línea de comandos** te vas a encontrar en la carpeta raíz de tu usuario \(generalmente en `/Users/tu_nombre_de_usuario`\).

Puedes volver a esta carpeta en cualquier momento utilizando el comando:

```text
$ cd ~
```

Ese carácter `~` es difícil de encontrar en el teclado a veces. Si no lo encuentras pide ayuda!

### La carpeta padre

Existen dos nombres de carpeta especiales que se utilizan para referirse a la carpeta actual y a la carpeta padre.:

* `.` se refiere a la carpeta actual
* `..` se refiere a la carpeta padre.

Por ejemplo, si nos encontramos en la ruta `/Users/germanescobar/Projects` y ejecutamos:

```text
$ cd ..
```

La nueva ubicación será `/Users/germanescobar`.

Puedes utilizar `..` en tus **rutas relativas**. Por ejemplo, si te encuentras en una carpeta `images` y quieres ir a una carpeta `fonts` que está al lado de `images` puedes ejecutar:

```text
$ cd ../fonts
```

Esa ruta `../fonts` lo que está diciendo es: vaya a la carpeta padre y después ingrese a la carpeta `fonts`.

## Creando una carpeta

Para crear una carpeta utiliza el comando `mkdir` seguido del nombre de la carpeta que quieres crear en la ubicación actual. Por ejemplo:

```text
$ mkdir Projects
```

El último comando crea la carpeta `Projects` dentro de la ubicación actual. Sin embargo, `mkdir` **no te cambia de ubicación automáticamente**. Para eso debes ejecutar:

```text
$ cd Projects
```

Nuestra recomendación es que crees esa carpeta `Projects` dentro de la raíz de tu usuario para todos tus proyectos.

