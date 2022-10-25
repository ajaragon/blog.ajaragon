---
title: Sobre Hugo
weight: 3
menu:
  main: {}
draft: false

---

*Hugo es uno de los generadores de sitios estáticos de fuente abierta más populares.*
*Con su increíble velocidad y flexibilidad, Hugo hace que crear sitios web vuelva a ser divertido.*
[**Sobre Hugo.**](https://gohugo.io/about/what-is-hugo/)

![Alt text](/Hugo_logo.svg)

*Hugo emplea una fuente de directorios y plantillas para crear gracias a ellos sitios web.*

###### Empezar a crear un sitio propio web

>Si escribo en el terminal:

>>```shell
>>hugo new site +nombreDeNuestoSitioWeb
>>```

>Lo que va a realizar Hugo es una descarga en mi equipo de los directorios y archivos desde donde se va a crear mi sitio.

>Ahora lo que necesito es descargar un tema, pero no es estrictamente necesario.
>No obstante, yo si voy a servirme de una plantilla de Hugo.

>>Dentro de la página de Hugo, hay que ir a *Themes*. Allí se puede encontrar, entre una lista de temas, la plantilla que nos convenga.

>>Yo utilicé el tema llamado *"Colordrop"*: 

>>[*------ Colordrop ------*](https://themes.gohugo.io/themes/colordrop/)

>>Clickamos sobre él y vamos al apartado *"installation"*. Se puede elegir entre varios métodos. Elegimos el que más nos convenzca.

>>Lo que me resultó más sencillo y me causó menos problemas a mí fue el descargar desde GitHub el zip. Este archivo se copia dentro de la carpeta *Themes* del sitio web de Hugo que hemos creado.

>Existen temas en los cuales es obligatorio la creación de una sección. Esta se crearía copiando en el terminal lo siguiente:

>>```shell
>>hugo new --kind chapter nombreDeNuestraSeccion/_index.md
>>```

>>A partir de esta sección ya se crean los diferentes directorios y archivos:

>>```shell
>>hugo new 'Directorio'/carpeta_1/C1_archivoMD_1.md
>>hugo new 'Directorio'/carpeta_1/C1_archivoMD_2.md
>>hugo new 'Directorio'/carpeta_2/C2_archivoMD_1.md
>>```

>>Sin embargo, también se puede llevar a cabo la creación de carpetas y archivos desde la interfaz gráfica de *Visual Studio Code* o del software que empleemos.

>Después, dentro de los archivos de "markdown" que hemos creado, cambiamos el estado de *draft* de todos a falso.

>>{{< figure src="/capturaDraft.png?width=1500" title="Ejemplo de cómo queda el *draft*" >}}

>En algunos temas, se explica cómo cambiar el aspecto visual básico del sitio web. Sólo hay que escribir o modificar lo que se indique en la página del tema que empleemos.

>>[*Cambiar el estilo del sitio web(tema de "Colordrop"):*](https://themes.gohugo.io/themes/colordrop/)
>>![Alt text](/capturaCambiarEstilo.png)

>A partir de aquí ya podemos editar lo que queramos para personalizar nuestra página.

>Solamente quedaría correr Hugo. Para ello lo haremos desde el terminal. Primero iremos a la carpeta de Hugo y después al directorio del sitio web.

>>```shell
>>cd Hugo
>>cd directorioSitioWeb
>>hugo server
>>```

>Tras escribir el comando de *"Hugo server"* se iniciará el sitio web. Para finalizar, abriremos el enlace en un navegador.

* * *
