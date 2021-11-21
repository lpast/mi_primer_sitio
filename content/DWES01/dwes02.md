---
title: "Apartado 2. Proceso de comunicación Cliente-Servidor"
date: 2021-11-18T21:41:25+01:00
draft: false
---

**ARQUITECTURA CLIENTE/SERVIDOR**

Se distinguen tres elementos principales:

1.- El _cliente_: navegadores web.

2.- _Internet_: es el medio por el que fluye la comunicación.

3.- El _Servidor_, encargado de responder las solicitudes del cliente.

**PROCESO DE COMUNICACION CLIENTE-SERVIDOR**

1.-  Un usuario introduce la URL  de la página que quiere visitar en el navegador. Indicando la máquina donde está, el protocolo usado y el puerto por el que se realiza la solicitud.

2.-  El navegador envía solicitud al servidor.

2.1- Si existe código PHP, se ejecuta.
    
2.2- Se ejecutan scripts.
    
3.-  Se hacen las consultas a la Base de Datos.

4.-  El servidor generará na página con HTML y tal vez JavaScript.

5.-  El servidor envía la página al navegador.

6.-  El navegador recibe la página, interpreta y usa el HTML para construirla. En caso de haber Scrips se ejecutarían.

7.-  Se muestra el contenido de la página web solicitda.

8.-  Todo será procesado por Javascript. Interactúara contigo respondiendo a tus eventos, hasta que cierres la página.

El siguiente diagrama refleja los pasos citados anteriormente.


![Proceso de carga](/images/proceso_carga_web.png)



