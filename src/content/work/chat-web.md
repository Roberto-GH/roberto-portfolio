---
title: Chat Web AI
publishDate: 2019-12-01 00:00:00
img: /assets/stock-2a.jpg
imgRes: /assets/stock-2b.jpg
link: https://chat-web.roberto-londono.website/
img_alt: Chat web capture
description: |
  API and interface that allows you to query an AI and interact with it conversationally.
tags:
  - Spring Boot
  - Svelte
  - Open AI
---

In Web Chat my main focus was to implement an API with methods that access the different resources offered by ChatGPT, adding security and abstraction so that it becomes a scalable development.

This was done with Spring Boot using tools such as Spring Security, allowing the addition of an authorization layer that allows secure access.

At the Front-End level, I used Svelte as a development tool, thus creating an interface similar to the chat we conventionally use, although it is a web application, a responsive design was included so that the app is accessible from different devices.

You can use it in your day to day is very useful !!!!. It should be noted that it is under the free Open AI cap, so it has limited use.

The source code for the API here: https://github.com/Roberto-GH/chatgpt-api

The source code for the front-end here: https://github.com/Roberto-GH/chatbot-web

In this case, the back-end was deployed in AWS through the ECS service (Elastic Container Service) and
Fargate that makes it easy to run and scale containerized data processing workloads.

For the front-end use Netlify, a platform designed for the deployment of static websites.