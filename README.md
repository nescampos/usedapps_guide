---
title: "Tutorial useDapp"
description: Tutorial para aprender a usar Dapp.
author: Néstor Campos
lang: es
sidebar: true
tags: ["useDapp", "ethereum", "react"]
skill: beginner
published: 2021-05-30
---

# Tutorial useDapp

## Introducción

El propósito de este tutorial es entender cómo puedes crear dApps utilizando **useDapp** en React.

## Instalación

Para comenzar a trabajar con **useDapp**, debe tener un entorno React funcionando.

Luego, agrega el siguiente paquete npm *@usedapp/core* a su proyecto:

<details>
  <summary>Con NPM</summary>
  
  ```sh
  npm install @usedapp/core
  ```
</details>

<details>
  <summary>Con Yarn</summary>
  
  ```sh
  yarn add @usedapp/core
  ```
</details>

## Configuración

Lo primero que debes hacer es configurar DAppProvider con configuración opcional y envolver toda su aplicación en él. Puedes leer sobre la configuración [aquí](https://usedapp.readthedocs.io/en/latest/core.html#config).


<details>
  <summary>Ver un ejemplo</summary>
  
  ```javascript
  <DAppProvider>
    <App /> {/* Wrap your app with the Provider */}
  </DAppProvider>
  ```
</details>

