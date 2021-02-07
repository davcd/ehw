# Extended hello world

> **Extended hello world** aims to:
> - Improve your first contact with a language, framework, or library
> - Improve your coding skills through practice
> - Be the starting point for your new project

## Table of contents

- [Introduction](#introduction)
    - [Template](#template)
    - [App](#app)
- [Resources](#resources)
- [Contributing](#contributing)

## Introduction

**Extended hello world** consists in a set of *apps* and *templates*.

### Template

A *template* is a set of definitions and rules defining an **scenario**. It will be the guide to implement an *app*.

Every *template* must:

- Be based on a common real-world scenario.
- Strictly define the scope, including all the necessary documentation. (i.e.: contract for an API, ...)
- Include e2e tests
- Be properly categorized (i.e.: back-end, front-end, cloud,...)

Every *template* should:

- Have a reasonable scope

Every *template* can:

- Encourage the introduction of a specific software design pattern
- Encourage implementation through a specific software development process

> Naming convention: ```ehw_<template-name>``` (i.e.: ```ehw_cart-rest-api```)

### App

An *app* is the runnable **code** implementation of a *template*.

One *template* can be implemented by many *apps*, each of which can be differentiated by programming language,
framework, library, code style, ... Or just the author!

Every *app* must:

- Meet the *template* requirements
- Use best practices
- Use the KISS principle
- Include documentation of how to run the code

Every *app* should:

- Be containerized

> Naming convention: ```ehw_<template-name>_<language>-<framework-library-runtime>``` (i.e.: ```ehw_cart-rest-api_java-spring```, ```ehw_cart-rest-api_ts-deno```)

## Resources

### back-end

- **cart-rest-api**: Simplified REST API for an e-commerce shopping cart.
  - Javascript - Node
  > WIP, currently separating template and app from [this repo](https://github.com/davcd/cart-rest-api)

## Contributing

Feel free to link your *templates* or *apps*!
