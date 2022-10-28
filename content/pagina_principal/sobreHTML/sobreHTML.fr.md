---
title: About HTML
weight: 4
menu:
  main: {}
draft: false

---

>Tout se passe tant que le port correspondant est ouvert ou que les conditions de la configuration du pare-feu de notre système d'exploitation permettent la connexion.

>Le protocole de transfert de données hypertexte est alors lancé : *HTTP*. Une application dépendant de ce protocole est constamment à l'écoute de toute demande de livraison de données sur le port 80. Le navigateur envoie une demande à un serveur. Il le trouve après avoir trouvé son IP associé à un nom de domaine. Pour ce faire, il accède au répertoire *etc/host* (dans le cas d'Ubuntu) du client. 

>Le serveur accepte la demande et recherche les documents souhaités par le client. Si tout est correct, il commence à télécharger les documents : fichiers *html*, javascript, css, images ou vidéos. Sinon, si le serveur a pu trouver la ressource, il lancera une erreur 404.

>Le PC de l'utilisateur reçoit le paquet sous forme de uns et de zéros. Le navigateur le traduit au format UTF-8 pour pouvoir lire le document *html*. Enfin, elle le schématise en nœuds et donne à chacun d'eux une hiérarchie. De cette façon, il rend les balises dans l'ordre et exécute le code ou l'image ou la vidéo de la page web contenue dans ces balises.

{{<mermaid align="center">}}
graph TD;
    A[Le navigateur lit le htmll] -->B(revoir les noeuds dans l'ordre) -->C{le document a-t-il des atouts ?};
    C -- |Sí| -->D(télécharger les assets) -->E[rend le document];
    C -- |No| -->F[rend directement le document];
{{</mermaid>}}

* * *

