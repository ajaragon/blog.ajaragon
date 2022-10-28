---
title: About HTML
weight: 4
menu:
  main: {}
draft: false

---

>Everything happens as long as the corresponding port is open or the conditions of the firewall configuration of our operating system allow the connection.

>The hypertext data transfer protocol is then started: *HTTP*. An application dependent on this protocol is constantly listening for any request for data delivery on port 80. The browser sends a request to a server. It finds it after finding its IP associated with a domain name. To do this, it accessed the *etc/host* directory (in the case of Ubuntu) of the client. 

>The server accepts the request and searches for the documents the client wants. If everything is correct, it starts downloading documents: *html* files, javascript, css, images or videos. Otherwise, if the server was able to find the resource, it will throw a 404 error.

>The user's PC receives the package as ones and zeros. The browser is in charge of translating it into UTF-8 format to be able to read the *html* document. To finally schematize it in nodes and thus give each one a hierarchy. In this way, it renders the tags in order and executes the code or the image or video of the web page contained in these tags.

{{<mermaid align="center">}}
graph TD;
    A[browser reads html] -->B(review the nodes in order) -->C{does the document have assets?};
    C -- |Sí| -->D(download the assets) -->E[renders the document];
    C -- |No| -->F[directly renders the document];
{{</mermaid>}}

* * *
