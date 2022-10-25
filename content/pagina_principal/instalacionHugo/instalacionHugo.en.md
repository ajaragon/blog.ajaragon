---
title: About how to install Hugo
weight: 2
menu:
  main: {}
draft: false

---

###### DOWNLOAD HUGO

-- This is the Hugo page about its installation on different operating systems: 
[**page from where to download Hugo.**](https://gohugo.io/getting-started/installing/)

In my case, I am going to list the necessary steps to download and install it in Ubuntu with the help of *snapd*. 

>-- Open the terminal and, in it, copy the following command:

>>```shell
>>sudo apt-get install snapd snapd-xdg-open
>>```

>>This allows to run the *Snap Store* services, which will help us to install Hugo in the next step.

###### INSTALL HUGO

>-- Now you can install Hugo. Type the following line in the terminal:

>>```shell
>>sudo snap install hugo --classic
>>```

>>By adding *"classic "* we cause the installer to download the latest stable version of the software.

>>-- Finally, you can check in the terminal the version that we have downloaded:

>>```shell
>>hugo version
>>```

>>{{<youtube lKT-tztvIEU>}}

* * *