---
title: À propos d'Hugo
weight: 3
menu:
  main: {}
draft: false

---

*Hugo est l'un des constructeurs de sites statiques à code source ouvert les plus populaires.*
*Avec sa vitesse et sa flexibilité incroyables, Hugo rend la création de sites Web à nouveau amusante.*
[**A propos d'Hugo.**] (https://gohugo.io/about/what-is-hugo/)

![Texte alternatif](/Hugo_logo.svg)

*Hugo utilise une source de répertoires et de modèles pour créer des sites web avec ceux-ci.*

###### Commencer à créer son propre site web

>Si je tape dans le terminal :


>>```shell
>>hugo new site +nombreDeNuestoSitioWeb
>>```

>Ce que Hugo va faire, c'est télécharger sur mon ordinateur les répertoires et les fichiers à partir desquels mon site va être créé.

>Maintenant, ce dont j'ai besoin, c'est de télécharger un thème, mais ce n'est pas strictement nécessaire.
>Cependant, je vais utiliser l'un des modèles d'Hugo.

>>Dans la page Hugo, allez dans *Thèmes*. Vous y trouverez, parmi une liste de thèmes, le modèle qui vous convient.

>>J'ai utilisé le thème appelé *"Colordrop"* : 

>>[*------ Colordrop ------*](https://themes.gohugo.io/themes/colordrop/)

>>Cliquez dessus et allez à la section *"installation"*. Vous pouvez choisir entre plusieurs méthodes. Choisissez celui qui vous convient le mieux.

>>Ce qui était plus facile et me posait moins de problèmes était de télécharger le fichier zip depuis GitHub. Ce fichier est copié dans le dossier *Themes* du site web Hugo que nous avons créé.

>Il existe des thèmes pour lesquels la création d'une section est obligatoire. On le crée en copiant dans le terminal ce qui suit :

>>```shell
>>hugo new --kind chapter nomDeNotreSection/_index.md
>>```

>>À partir de cette section, les différents répertoires et fichiers sont créés :

>>```shell
>>hugo new 'Répertoire'/fichier_1/C1_archiveMD_1.md
>>hugo new 'Répertoire'/fichier_1/C1_archiveMD_2.md
>>hugo new 'Répertoire'/fichier_2/C2_archiveMD_1.md
>>```

>>Cependant, vous pouvez également créer des dossiers et des fichiers à partir de l'interface graphique de *Visual Studio Code* ou de tout autre logiciel que vous utilisez.

>Ensuite, dans les fichiers markdown que nous avons créés, nous changeons le statut *draft* de tous les fichiers en false.

>>{{< figure src="/capturaDraft.png?width=1500" title="Exemple de ce à quoi ressemble le *draft*." >}}
>> ![Texte alt](/capturaDraft.png?width=1500)

>Dans certaines rubriques, il est expliqué comment modifier l'aspect visuel de base du site web. Il suffit de taper ou de modifier ce qui est indiqué sur la page du thème que vous utilisez.

>>[*Changer le style du site web(thème Colordrop):*](https://themes.gohugo.io/themes/colordrop/)

>A partir de là, nous pouvons modifier ce que nous voulons pour personnaliser notre page.

>Il ne reste plus qu'à exécuter Hugo. Pour cela, nous allons le faire depuis le terminal. Nous allons d'abord nous rendre dans le dossier Hugo, puis dans le répertoire du site web.

>>```shell
>>cd Hugo
>>cd répertoireSiteWeb
>>Hugo server
>>```

>Après avoir tapé la commande *"Hugo server"*, le site web démarrera. Enfin, ouvrez le lien dans un navigateur.

* * *