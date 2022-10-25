---
title: Sur la manière d'installer Hugo
weight: 2
menu:
  main: {}
draft: false

---

#### TÉLÉCHARGER HUGO

-- Il s'agit de la page d'Hugo sur la façon de l'installer sur différents systèmes d'exploitation : 
[**page d'où télécharger Hugo.**] (https://gohugo.io/getting-started/installing/)

Dans mon cas, je vais énumérer les étapes pour le télécharger et l'installer sur Ubuntu avec l'aide de *snapd*.

>-- Ouvrez le terminal et copiez la commande suivante dans celui-ci :

>>```shell
>>sudo apt-get install snapd snapd-xdg-open
>>```

>>Cela vous permet d'exécuter les services *Snap Store*, qui vous aideront à installer Hugo à l'étape suivante.

###### INSTALLER HUGO

>-- Maintenant vous pouvez installer Hugo. Tapez la ligne suivante dans le terminal :

>>```shell
>>sudo snap install hugo --classic
>>```

>>En ajoutant *"classic"*, le programme d'installation téléchargera la dernière version stable du logiciel.

>>-- Enfin, vous pouvez vérifier la version téléchargée sur le terminal :

>>```shell
>>hugo version
>>```

>>{{<youtube lKT-tztvIEU>}}

* * *

git add . /*
git commit -m ""
git push origin main
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