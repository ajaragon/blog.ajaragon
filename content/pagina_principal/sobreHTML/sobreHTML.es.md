---
title: Sobre cómo se carga HTML
weight: 4
menu:
  main: {}
draft: false

---

>Todo ocurre mientras el puerto correspondiente se encuentra abierto o las condiciones de la configuración del firewall de nuestro sistema operativo permite la conexión.

>Se inicia entonces el protocolo de transferencia de datos de hipertexto: *HTTP*. Una aplicación dependiente de este protocolo se encarga constantemente de escuchar cualquier petición de entrega de datos por el pueto 80. El navegador manda una petición a un servidor. Lo halla tras encontrar su IP asociada a un nombre de dominio. Para ello, accedió al directorio *etc/host* (en el caso de Ubuntu) del cliente. 

>Por su parte, el servidor acepta la solicitud y busca los documentos que quiere el cliente. Si todo está correcto, comienza la descarga de documentos: archivos *html*, javascript, css, imágenes o vídeos. En caso contrario, si el servidor pudo encontrar el recurso, lanzará un error 404.

>Al pc del usuario le llega el paquete como unos y ceros. El navegador se encarga en traducirlo al formato UTF-8 para poder leer el documento *html*. Para finalmente esquematizarlo en nodos y así darle a cada uno una jerarquía. De esta manera, renderiza por orden las etiquetas y ejecuta el código o la imagen o vídeo de la página web contenidos en estas etiquetas.

{{<mermaid align="center">}}
graph TD;
    A[navegador lee html] -->B(revisa los nodos por orden) -->C{¿el documento tiene assets?};
    C -- |Sí| -->D(descarga los assets) -->E[renderiza el documento];
    C -- |No| -->F[directamente renderiza el documento];
{{</mermaid>}}

* * *



