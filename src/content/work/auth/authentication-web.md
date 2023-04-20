---
title: Authentication Web
publishDate: 2020-03-04 00:00:00
img: /assets/stock-3a.jpg
imgRes: /assets/stock-3b.jpg
link: http://authentication-web.s3-website-us-east-1.amazonaws.com/#/home
img_alt: User authentication
description: |
  I developed a platform that allows to authenticate and manage users.
tags:
  - Spring Boot
  - JWT
  - Angular
  - MySQL
---

Authentication Web is a login page created with tools like Spring Boot and Spring Security allowing me to authenticate, authorize and manage users and roles. This using the JSON Web Token (JWT) standard that defines a compact and autonomous way to transmit information securely between parties as a JSON object. In addition, including a refresh token method allowing to maintain the user's session in the browser safely, regardless of the use of cookies.

As for the user interface, I used Angular as front-end technology, allowing me to adopt one of the most used architectures in recent years, Single Page Applications (SPAs). As for the styles part, use Bootstrap that brings a set of front-end tools, thus achieving fast, efficient and scalable development.

The source code for the API here: https://github.com/Roberto-GH/authentication-api

The source code for the front-end here: https://github.com/Roberto-GH/authentication-web

It should be noted that the back-end is deployed on AWS through the Elastic Beanstalk service that automatically manages the deployment,
from capacity provisioning, load balancing and autoscaling to Monitoring the state of the application.

For its part, the front-end is located in a back-end of S3.