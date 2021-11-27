---
title: "Apartado 2. Proceso de comunicación Cliente-Servidor"
date: 2021-11-18T21:41:25+01:00
draft: false
---

** CLIENT / SERVER ARCHITECTURE **

Three main elements are distinguished:

1.- The _cliente_: web browsers.

2.- _Internet_: it is the means through which communication flows.

3.- The _Server_, in charge of responding to the client's requests.

** CLIENT-SERVER COMMUNICATION PROCESS **

1.- A user enters the URL of the page he wants to visit in the browser. Indicating the machine where it is, the protocol used and the port through which the request is made.

2.- The browser sends a request to the server.

2.1- If there is PHP code, it is executed.
    
2.2- Scripts are executed.
    
3.- Queries are made to the Database.

4.- The server will generate a page with HTML and maybe JavaScript.

5.- The server sends the page to the browser.

6.- The browser receives the page, interprets and uses the HTML to build it. If there were Scrips they would be executed.

7.- The content of the requested web page is displayed.

8.- Everything will be processed by Javascript. They will interact with you by responding to your events, until you close the page.

The following diagram reflects the steps cited above.


![Proceso de carga](/images/proceso_carga_web.png)



