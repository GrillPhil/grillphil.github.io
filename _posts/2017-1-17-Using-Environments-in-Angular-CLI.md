---
layout: post
title: Using Environments in Angular CLI
---

Building web apps typically requires multiple development and production environments. For example you might have a local web api endpoint you want to use during development for debugging, a testing endpoint and a production endpoint. Same applies for debug/logging flags or oauth configurations.

Before I started using the Angular CLI to create my projects I used to do environment configuration using Powershell scripts. Angular CLI offers a much more convenient way with their built in environment system.

