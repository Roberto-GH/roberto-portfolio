---
title: Telefonica de Perú
publishDate: 2019-12-01 00:00:00
img: /assets/movistar.png
imgRes: /assets/movistar.png
link: https://www.movistar.com.pe/soporte-reclamos-disconformidad/registro-de-reclamos
img_alt: Movistar capture
description: |
  Portal público Movistar Perú, sección reclamos.
tags:
  - Java
  - JSP
  - Azure
  - Spring boot
---

Telefonica de Perú cuenta con un portal especializado que le ofrece al cliente poder registrar sus reclamos permitiendo asi cumplir con las regulaciones del organismo supervisor de inversión privada en telecomunicaciones (OSIPTEL).

Para este proyecto se implemento un back for frontend hecho en spring boot que permite consumir los servicios requeridos para esta funcionalidad y exponiendolos com api rest al frontend de una forma mas centralizada y facil de usar para el cliente front end.

También se construyo un config server (spring cloud) cumpliendo así con los lineamientos de desarrollo de telefonica obteniendo como resultado la centralización de configuraciones de la aplicación.