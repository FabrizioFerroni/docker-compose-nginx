# Server web Nginx y Docker

Se utilizo docker-composer para montar un servidor web nginx que corre sobre el puerto 80 y muestra un titulo y un parrafo mostrando que esta corriendo todo ok

## Pasos para ejecutar el server web:

1. Abrir la terminal
2. Clonar el repositorio
3. Entrar a la carpeta con `cd docker-compose-nginx`
4. Correr el docker compose con el comando `docker compose up` para que arranque el server web
5. Dirigirse a la dirección [http://localhost/](http://localhost/) y mostrara la plantilla web
6. Para parar el servidor correr el comando `docker compose stop` y para volverlo a iniciar el comando `docker compose start`
7. Para terminar la imagen de docker correr el comando `docker compose down` y listo.