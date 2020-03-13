# Git y GitHub

**Git** te permite guardar un historial de cambios de tus proyectos y trabajar con otros desarrolladores en un mismo proyecto.

El concepto más importante de **git** es el **commit**. Un **commit** es una fotografía de tu proyecto en un momento determinado. La forma en que **git** almacena el historial de cambios de tu proyecto es creando una cadena de **commits**.

**Git** es una aplicación de consola con varios subcomandos que nos permiten, entre otras cosas, hacer **commits**, ver los cambios a los que no les hemos hecho **commit**, listar los **commits**. y ver la diferencia entre **commits**.



## Instalación

Para descargar e instalar Git:

* Si estás en Mac o Linux ingresa a [https://git-scm.com/download](https://git-scm.com/download).
* Si estás en Windows ingresa a [https://desktop.github.com/](https://desktop.github.com/).



## Primeros pasos

Lo primero que debes hacer después de que has instalado **git** es configurar el nombre y correo que se va a utilizar para firmar cada **commit** que hagas. Utiliza los comandos `git config --global user.name <name>` y `git config --global user.email <email>`.

Por ejemplo, si tu nombre fuera "Pedro Perez" utilizarías el siguiente comando:

```text
$ git config --global user.name Germán Escobar
```

Y asumiendo que el correo es "pedro.perez@gmail.com" utilizarías el siguiente comando:

```text
$ git config --global user.email pedro.perez@gmail.com
```

### Trabajando en un proyecto

El flujo de trabajo más simple con **git** es el siguiente

1. Inicializa el repositorio \(esto va a crear una carpeta oculta `.git` dentro del proyecto\):

   ```text
    $ git init
   ```

2. Trabaja en el código: crea, modifica y elimina archivos.
3. Prepara los cambios que vas a incluir en el siguiente commit. Para incluir todos los cambios utiliza:

   ```text
    $ git add .
   ```

4. Crea el commit:

   ```text
    $ git commit -m 'El mensaje que describe los cambios'
   ```

5. Repite los pasos 2, 3 y 4.

### Resumen de los comandos más importantes

* `git config --global user.name <name>`: define el nombre que se va a utilizar en los commits de forma global \(para el usuario actual\).
* `git config --global user.email <email>`: define el correo electrónico que se va a utilizar en los commits de forma global \(para el usuario actual\).
* `git init`: este comando se encarga de iniciar el repositorio \(esto va a crear una carpeta oculta `.git` en la carpeta donde ejecutes este comando\).
* `git add .`: prepara los archivos para el `commit`.
* `git commit -m <descripción de los cambios>`: crea un commit a partir de los cambios que están en el index con el mensaje que se le pase a la opción `-m`.
* `git status`: muestra la lista de archivos con cambios desde el último commit y los que van a ser incluídos en el siguiente commit.

## GitHub

[Github](https://github.com) es un servicio que nos brinda la posibilidad de crear una réplica de nuestro repositorio local en la nube.

Si aún no tienes una cuenta en [Github](https://github.com) es hora de crear una antes de continuar.



