---
title: Sobre cómo instalar Hugo
weight: 2
menu:
  main: {}
draft: false

---

###### DESCARGAR HUGO

-- Esta es la página de Hugo sobre su instalación en diferentes sistemas operativos: 
[**página desde donde descargar Hugo.**](https://gohugo.io/getting-started/installing/)

En mi caso, voy a enumerar los pasos necesarios para descargarlo e instalarlo en Ubuntu con la ayuda de *snapd*. 

>-- Se abre el terminal y, en él, se debe copiar la siguiente orden:

>>```shell
>>sudo apt-get install snapd snapd-xdg-open
>>```

>>Esto permite correr los servicios de la *Snap Store*, la cual nos ayudará a instalar Hugo en el siguiente paso.

###### INSTALAR HUGO

>-- Ahora ya se puede instalar Hugo. Se escribe entonces la siguiente linea en el terminal:

>>```shell
>>sudo snap install hugo --classic
>>```

>>Al añadirle *"classic"* lo que provocamos es que el instalador se vaya a descargar la última versión estable del software.

>>-- Por último, se puede comprobar en el terminal la versión que tenemos descargada:

>>```shell
>>hugo version
>>```

>>{{<youtube lKT-tztvIEU>}}

* * *








