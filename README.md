Flati
=====================

Proyecto
-------------------
[Enlace al demo](https://pacch.github.io/Flati/app/)

Instalación(DESARROLLO)
-----------------------
Pasos levantar el ambiente de desarrollo con node ejecutar:

1. npm install (para instalar las dependecias de desarrollo)
2. gulp serve (para levantar nuestro servidor)

En caso no contar con node instalado la aplicación puede ser visualizada en la ruta app/index.html

Resumen del proyecto
--------------------
El proyecto ha sido realizado desde 0 con:
* Sass
* Pug ~~Jade~~
* Gulp

Librerias externas:
No se usaron librerias externas a excepción de:
* JQuery
* normalize.css
* Librerias para compilar con gulp

Estructura de carpetas
----------------------

```scss
ordenador de serie/
|- app/
|  |- css/
|  |  |- style.css (CSS compilado)

|  |- fonts/
|  |  |- ... (Icomoon fonts)

|  |- js/
|  |  |- app.js (Jquery)

|  |- scss/ (Archivos Sass)
|  |  - base/
|  |  - components/
|  |  - layout/
|  |  - vendor/
|  |  |- style.scss (includes)

|  |- views/ (Archivos Pug ~~Jade~~)
|  |  - inc/ (Header, footer)
|  |  |- index.pug 

|  |- index.html

|- .editorconfig (indentación fijada a 4 espacios)
|- .gitattributes
|- .gitignore (obviamos los modulos de node)
|- gulpfile.js (listo para compilar el proyecto)
|- package.json
# Flati
