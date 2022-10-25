---
title: About Hugo
weight: 3
menu:
  main: {}
draft: false

---

*Hugo is one of the most popular open source static site generators.*
*With its incredible speed and flexibility, Hugo makes creating websites fun again.*
[**About Hugo.**](https://gohugo.io/about/what-is-hugo/)

![Alt text](/Hugo_logo.svg)

*Hugo uses a source of directories and templates to create websites thanks to them.*

###### Start creating your own website

>If I type in the terminal:

>>```shell
>>hugo new site +nombreDeNuestoSitioWeb
>>```

>What Hugo is going to do is to download to my computer the directories and files from where my site is going to be created.

>Now what I need is to download a theme, but it is not strictly necessary.
>However, I am going to use one of Hugo's templates.

>>Inside the Hugo page, go to *Themes*. There you can find, among a list of themes, the template that suits you.

>>I used the theme called *"Colordrop"*: 

>>[*------ Colordrop ------*](https://themes.gohugo.io/themes/colordrop/).

>>Click on it and go to the section *"installation"*. You can choose between several methods. We choose the one that more convinces us.

>>What I found easier and caused me less problems was to download from GitHub the zip. This file is copied into the *Themes* folder of the Hugo website we have created.

>There are themes in which the creation of a section is mandatory. This would be created by copying in the terminal the following:

>>```shell
>>hugo new --kind chapter nameOfOurSection/_index.md
>>```

>>From this section the different directories and files are created:

>>```shell
>>hugo new 'Directory'/folder_1/C1_fileMD_1.md
>>hugo new 'Directory'/folder_1/C1_fileMD_2.md
>>hugo new 'Directory'/folder_2/C2_fileMD_1.md
>>```

>>However, the creation of folders and files can also be done from the graphical interface of *Visual Studio Code* or whatever software we use.

>Then, inside the markdown files we have created, we change the *draft* status of all of them to false.

>>{{< figure src="/capturaDraft.png?width=1500" title="An example of how the *draft* looks like" >}}

>In some topics, it is explained how to change the basic visual appearance of the web site. Just type or modify what is indicated on the page of the theme you are using.

>>[*Change the style of the website(Colordrop theme):*](https://themes.gohugo.io/themes/colordrop/)
>>![Alt text](/capturaCambiarEstilo.png)

>From here we can edit whatever we want to customize our page.

>All that remains is to run Hugo. To do this we will do it from the terminal. First we will go to the Hugo folder and then to the website directory.

>>```shell
>>cd Hugo
>>cd WebSiteDirectory
>>hugo server
>>```

>After typing the command *"Hugo server"* the web site will start. To finish, we will open the link in a browser.

* * *