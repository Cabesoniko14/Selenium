# Selenium Web Scraping

<img src="https://promdevelop.com/wp-content/uploads/2021/06/selenium-logo-1024x531.png" alt="Selenium Logo" width="500" height="259">


Introducción a los conceptos básicos de Selenium para Web Scraping.

## Table of Contents

- [Introduccióon](#Introducción)
- [Instalaciónon](#Instalación)
  - [Windows/Mac Intel](#Windows)
  - - [Windows/Mac Intel](#Mac M1)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introducción

En este repositorio, se tiene un breve tutorial de como emplear la librería de Selenium (en Python) para poder adentrarse un poco al Web Scraping y sus tareas más básicas.

## Instalación

Para poder correr Selenium en la computadora, ofrecemos dos opciones: una para arquitecuta **AMD64** y otra para **ARM64**. Es decir, una para Windows y otra para Mac M1. A continuación sigue los pasos para poder correr los notebooks.

### Windows

En la carpeta de *Link a la carpeta de Bingus* se encuentra el ambiente de Docker para poder correr los ejercicios de clase con todas las librerías necesarias instaladas. Los pasos son los siguientes

**1. Descarga la carpeta**

Descarga el repositorio en tu computadora.

**2. Asegúrate de tener los puertos correctos**

En el Dockerfile, asegúrate de tener los puertos de tu elección bien seleccionados (en el caso de que los que tenemos por default en el Dockerfile ya estén ocupados en tu computadora).

**3. Corre el Docker**

En tu terminal, estando en la carpeta *link a la carpeta*, ejecuta:

<code>docker compose up --build</code>

Asegúrate de tener Docker Desktop abierto-

**4. Abre la aplicación en Chrome**

Entra a Docker Desktop, y en el contenedor de Selenium, selecciona abrir la página con los puertos. **Ojo!** Recuerda abrirlo en **Google Chrome**.

### Mac M1



