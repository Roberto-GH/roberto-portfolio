---
title: Chat Web AI
publishDate: 2019-12-01 00:00:00
img: css
imgRes: /assets/chat.png
link: https://chat-web.roberto-londono.website/
img_alt: Chat web capture
description: |
  API e interfaz que le permite consultar una IA e interactuar con ella de forma conversacional.
tags:
  - Spring Boot
  - Svelte
  - Open AI
---

En Web Chat mi enfoque principal fue implementar una API con m&eacute;todos que accedan a los diferentes recursos que ofrece ChatGPT, agregando seguridad y abstracci&oacute;n para que se convierta en un desarrollo escalable.

Esto se hizo con Spring Boot utilizando herramientas como Spring Security, permitiendo agregar una capa de autorizaci&oacute;n que permite el acceso seguro.

A nivel de Front-End utilic&eacute; Svelte como herramienta de desarrollo creando as&iacute; una interfaz similar al chat que usamos convencionalmente, aunque es una aplicaci&oacute;n web se incluye un dise&ntilde;o responsive para que la app sea accesible desde diferentes dispositivos.

Puedes utilizarlo en tu d&iacute;a a d&iacute;a es muy &uacute;til!!!!. Cabe destacar que se encuentra bajo el l&iacute;mite gratuito de Open AI, por lo que tiene un uso limitado.

El c&oacute;digo fuente de la API aqu&iacute;: https://github.com/Roberto-GH/chatgpt-api

El c&oacute;digo fuente del front-end aqu&iacute;: https://github.com/Roberto-GH/chatbot-web

En este caso, el backend se implemento en AWS a trav&eacute;s del servicio ECS (Elastic Container Service) y
Fargate que facilita la ejecuci&oacute;n y escalamiento de cargas de trabajo de procesamiento de datos en contenedores.

Para el front-end utilic&eacute; Netlify, una plataforma dise&ntilde;ada para el despliegue de sitios web est&aacute;ticos.