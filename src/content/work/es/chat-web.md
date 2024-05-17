---
title: Chat Web AI
publishDate: 2019-12-01 00:00:00
img: /assets/background-chat.jpg
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

En Web Chat mi enfoque principal fue implementar una API con métodos que accedan a los diferentes recursos que ofrece ChatGPT, agregando seguridad y abstracción para que se convierta en un desarrollo escalable.

Esto se hizo con Spring Boot utilizando herramientas como Spring Security, permitiendo agregar una capa de autorización que permite el acceso seguro.

A nivel de Front-End utilicé Svelte como herramienta de desarrollo creando así una interfaz similar al chat que usamos convencionalmente, aunque es una aplicación web se incluye un diseño responsive para que la app sea accesible desde diferentes dispositivos.

Puedes utilizarlo en tu día a día es muy útil!!!!. Cabe destacar que se encuentra bajo el límite gratuito de Open AI, por lo que tiene un uso limitado.

El código fuente de la API aquí: https://github.com/Roberto-GH/chatgpt-api

El código fuente del front-end aquí: https://github.com/Roberto-GH/chatbot-web

En este caso, el backend se implemento en AWS a través del servicio ECS (Elastic Container Service) y
Fargate que facilita la ejecución y escalamiento de cargas de trabajo de procesamiento de datos en contenedores.

Para el front-end utilicé Netlify, una plataforma diseñada para el despliegue de sitios web estáticos.