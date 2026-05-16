---
title: Authentication Web
publishDate: 2020-03-04 00:00:00
img: css
imgRes: /assets/auth.png
link: https://auth-web.roberto-londono.website/#/home
img_alt: User authentication
description: |
  Desarrollé una plataforma que permite autenticar y administrar usuarios.
tags:
  - Spring Boot
  - JWT
  - Angular
  - MySQL
---

Authentication Web es una p&aacute;gina de inicio de sesi&oacute;n creada con herramientas como Spring Boot y Spring Security que me permiten autenticar, autorizar y administrar usuarios y roles. Esto utilizando el est&aacute;ndar JSON Web Token (JWT) que define una forma compacta y aut&oacute;noma de transmitir informaci&oacute;n de forma segura entre partes como un objeto JSON. Adem&aacute;s, incluye un m&eacute;todo de token de actualizaci&oacute;n que permite mantener la sesi&oacute;n del usuario en el navegador de forma segura, independientemente del uso de cookies.
<br><br>
En cuanto a la interfaz de usuario, utilic&eacute; Angular como tecnolog&iacute;a front-end, lo que me permiti&oacute; adoptar una de las arquitecturas mas utilizadas en los &uacute;ltimos a&ntilde;os, las Aplicaciones de una sola p&aacute;gina (SPA). En cuanto a la parte de estilos, utiliza Bootstrap que trae un conjunto de herramientas front-end, logrando as&iacute; un desarrollo r&aacute;pido, eficiente y escalable.
<br><br>
El c&oacute;digo fuente de la API aqu&iacute;: https://github.com/Roberto-GH/authentication-api
<br><br>
El c&oacute;digo fuente del front-end aqu&iacute;: https://github.com/Roberto-GH/authentication-web
<br><br>
Cabe se&ntilde;alar que el backend se implementa en AWS a trav&eacute;s del servicio Elastic Beanstalk que administra autom&aacute;ticamente la implementaci&oacute;n, desde aprovisionamiento de capacidad, equilibrio de carga y escalado autom&aacute;tico hasta monitoreo del estado de la aplicaci&oacute;n.
<br><br>
Por su parte, el front-end se ubica en un bucket de S3.