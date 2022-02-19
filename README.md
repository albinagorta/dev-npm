INICIAR UN PROYECTO NPM
Primero abrimos nuestra terminal y nos posicionamos donde guardamos nuestros archivos.
Podemos crear una carpeta para nuestro proyecto con el comando
mkdir project_name nos movemos dentro de la carpeta con cd project_name ya dentro de la carpeta podemos iniciar:

Primeros pasos
git init: Para tener el control de cambios y versiones en nuestro proyecto
npm init: con este comando vamos a crear nuestro archivo de configuración del proyecto, el package.json
Luego nos saldrá lo siguiente
package name: el nombre de nuestro proyecto, generalmente es el nombre de la carpeta
version: version con la que iniciaremos el proyecto, generalmente aparece 1.0.0
description: descripcion breve del proyecto
entry point: punto de acceso a nuestro proyecto
test command: comando para gestionar los test
git repository: repositorio de github u otro servicio
keywords: palabras claves del proyecto
author**: nombre del autor y < correo > **license`: licencia que tendrá el proyecto

<h3>2da opción (para hacer package rápido)</h3>
Escribimos npm init -y y esto generará un package.json vacio para que lo configuremos más adelante.

<h3>3ra opción (configuramos algunos elementos)</h3>
Escribimos en nuestra terminal
npm set init.author.email "your@email"
npm set init.author.name "your name"
npm set init.license "license name"
npm init -y
Y se creará un package.json con los datos que seleccionamos.







!(https://raw.githubusercontent.com/albinagorta/dev-npm/main/a.jpg)