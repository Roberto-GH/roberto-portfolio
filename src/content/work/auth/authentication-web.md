---
title: Authentication Web
publishDate: 2020-03-04 00:00:00
img: /assets/stock-3a.jpg
imgRes: /assets/stock-3b.jpg
link: http://auth-web.roberto-londono.website.s3-website-us-east-1.amazonaws.com/#/home
img_alt: User authentication
description: |
  Desarrollé una plataforma que permite autenticar y administrar usuarios.
tags:
  - Spring Boot
  - JWT
  - Angular
  - MySQL
---

Authentication Web es una página de inicio de sesión creada con herramientas como Spring Boot y Spring Security que me permiten autenticar, autorizar y administrar usuarios y roles. Esto utilizando el estándar JSON Web Token (JWT) que define una forma compacta y autónoma de transmitir información de forma segura entre partes como un objeto JSON. Además, incluye un método de token de actualización que permite mantener la sesión del usuario en el navegador de forma segura, independientemente del uso de cookies.

En cuanto a la interfaz de usuario, utilicé Angular como tecnología front-end, lo que me permitió adoptar una de las arquitecturas más utilizadas en los últimos años, las Aplicaciones de una sola página (SPA). En cuanto a la parte de estilos, utiliza Bootstrap que trae un conjunto de herramientas front-end, logrando así un desarrollo rápido, eficiente y escalable.

El código fuente de la API aquí: https://github.com/Roberto-GH/authentication-api

El código fuente del front-end aquí: https://github.com/Roberto-GH/authentication-web

Cabe señalar que el backend se implementa en AWS a través del servicio Elastic Beanstalk que administra automáticamente la implementación, desde aprovisionamiento de capacidad, equilibrio de carga y escalado automático hasta monitoreo del estado de la aplicación.

Por su parte, el front-end se ubica en un bucket de S3.