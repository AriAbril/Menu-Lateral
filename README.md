# MenuLateral
 Ejercicio de menú lateral con HTML, SCSS, CSS y JSON.

 # Comandos NPM
 ## _Comandos utilizados en este proyecto_

 1.- Crear package.json ingresando la información del proyecto: $ npm init 
    O bien, si se desea el package.json con la configuración default: $ npm init -y

 2.- Instalar la dependencia de node: $ npm i node-sass

 Nota: 
 Para desinstalar la dependencia de node: $ npm uninstall node-sass
 Para instalar una dependencia específica de node: $ npm i node-sass@(versión)

 # Node-SASS
 Para convertir un archivo SCSS a CSS, ingresar la siguiente instrucción en el package.json:
  "script": {
      "build:css": "node-sass -watch --output-style expanded --precision 6 src/assets/scss/style.scss -o dist/css",
  } 

# GITHUB: 
Para bajar los cambios realizados en git: $ git pull origin main
Después de hacer modificaciones en los archivos se debe realizar lo siguiente: 

1.- $ git status (Para verificar los cambios que se relizaron.)
2.- $ git add . (Para agregar todos los cambios realizados.)
3.- $ git commit -m "Mensaje de lo que se modificó" (Comentario para validar cuáles cambios se realizaron o bien
sólo $ git commit.) 
4.- $ git status (Para ver si el commit se hizo de manera correcta.)
5.- $ git push origin main (Para subir los cambios que se realizaron al repo.)