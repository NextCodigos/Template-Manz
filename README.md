# Template-Manz
Explicación del Código
HTML Básico: La estructura del HTML contiene dos templates y un contenedor .data donde se añadirán dinámicamente los elementos clonados.
Templates:
<template class="image-template">: Contiene una estructura de un contenedor con un párrafo (<p>) y una imagen (<img>).
<template class="video-template">: Contiene un contenedor con un párrafo (<p>) y un video (<video>).
JavaScript:
Al cargar el DOM (DOMContentLoaded), se seleccionan ambos templates utilizando querySelector.
Se clonan los elementos de cada template y se personalizan antes de insertarlos en el contenedor .data.
El template de imágenes se clona 3 veces y se modifica el texto de su párrafo.
El template de videos se clona 2 veces, se define su src y se cambia el texto del párrafo correspondiente.
Cómo Usar el Proyecto
Clona o descarga el archivo HTML en tu máquina local.
Abre el archivo en tu navegador.
Verás que se generarán 3 contenedores con imágenes y 2 contenedores con videos, todos creados de forma dinámica a partir de los templates definidos.
