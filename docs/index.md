<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a name="readme-top"></a>

<!-- Badges -->
<p align="center">
  <a href="https://github.com/LeKEVIN5151/actividad_integradora_tcpip">
    <img src="https://img.shields.io/github/contributors/LeKEVIN5151/actividad_integradora_tcpip.svg?style=for-the-badge" alt="Contributors">
  </a>
  <a href="https://github.com/LeKEVIN5151/actividad_integradora_tcpip/network/members">
    <img src="https://img.shields.io/github/forks/LeKEVIN5151/actividad_integradora_tcpip.svg?style=for-the-badge" alt="Forks">
  </a>
  <a href="https://github.com/LeKEVIN5151/actividad_integradora_tcpip/stargazers">
    <img src="https://img.shields.io/github/stars/LeKEVIN5151/actividad_integradora_tcpip.svg?style=for-the-badge" alt="Stargazers">
  </a>
  <a href="https://github.com/LeKEVIN5151/actividad_integradora_tcpip/issues">
    <img src="https://img.shields.io/github/issues/LeKEVIN5151/actividad_integradora_tcpip.svg?style=for-the-badge" alt="Issues">
  </a>
</p>

<!-- PROJECT LOGO -->

<div align="center">
<p align="center">
  <img src="/images/logo.png" alt="Logo REFLEX" width="200"/>

<div align="center">
  <a href="https://github.com/LeKEVIN5151/actividad_integradora_tcpip">
    <img src="images/snake.webp" alt="Snake Game" width="400" height="324">
  </a>
</p>
<h3 align="center">Snake Game En Reflex!!!</h3>

<p align="left">En este proyecto te enseño a ejecutar el juego del snake en un entorno totalmente dockerizado.</p>

<h3 align="center">Built With</h3>

<div align="center">
  <a href="https://reflex.dev/">
    <img src="https://img.shields.io/badge/Reflex-FF5733?style=for-the-badge&logo=reflex&logoColor=white" alt="Reflex">
  </a>
  <a href="https://www.docker.com/">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  </a>

  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=black" alt="Docker">
  </a>
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

<h2 align="center">Para comenzar</h2>

<p align="left">
A continuación, te mostraremos cómo iniciar una aplicación desarrollada en Reflex y contenedorizada con Docker, para que puedas ejecutarla localmente en tu computadora dentro de un entorno Docker.
</p>

<h2 align="center">Todo lo necesario para la ejecución</h2>

<p align="left">
  1. <a href="https://unrc.gitlab.io/labredes/Docker/Docker_Instalacion/">Asegúrate de tener Docker instalado en tu sistema.</a>
</p>

<p align="left">
  2. Los Archivos necesarios los encontrarás en el <a href="https://github.com/LeKEVIN5151/actividad_integradora_tcpip/tree/main/actividad_integradora_tcpip/apps">siguiente link.</a>
</p>

<p align="left">
  En esta carpeta encontrarás cuatro archivos esenciales para ejecutar correctamente esta aplicación:
</p>

<p align="left">
  - <strong>game_snake.py</strong>: Este archivo contiene la aplicación desarrollada en Python.<br>
  - <strong>Dockerfile</strong>: Utilizado para crear el entorno necesario para ejecutar la aplicación.<br>
  - <strong>requirements.txt</strong>: Archivo de texto que enumera los requerimientos necesarios para la instalación.
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 align="center">Ejecución</h2>

<p align="left">
  1. Construye la imagen Docker (deberás tener los anteriores 3 archivos en la misma carpeta):
  <pre>
  <code>docker build -t snakegame .</code>
  </pre>
</p>

<p align="left">
  2. Ejecuta el contenedor Docker en modo host:
  <pre>
  <code>docker run --network host snakegame</code>
  </pre>
</p>

<p align="left">
  3. Accede a la aplicación en tu navegador web en:
  <pre>
  <code>http://localhost:3000</code>
  </pre>
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<h2 align="center">Contacto</h2>

<p align="left">
  <a href="https://www.instagram.com/kevinhaponiuk/">@instagram</a><br>
  <a href="https://www.facebook.com/kevin.haponiuk/">@facebook</a><br>
  Project Link: <a href="https://github.com/LeKEVIN5151/actividad_integradora_tcpip">https://github.com/LeKEVIN5151/actividad_integradora_tcpip</a><br>
  Mail: kevinhapo@gmail.com
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
