# Practica_docker
# Mi Aplicación
Este proyecto es una aplicación "Hola Mundo" que utiliza Apache, PHP y MySQL, configurada y ejecutada a través de Docker Compose.

## Prerrequisitos
Asegúrate de tener instalados los siguientes programas en tu sistema:
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Configuración del Archivo `.env`
Para manejar las variables de entorno, crea un archivo `.env` en el directorio raíz de tu proyecto. Este archivo debe contener las variables de entrono del proyecto.


## Construir y Ejecutar los Contenedores
Desde el directorio raíz del proyecto (mi_aplicacion), ejecuta los siguientes comandos para construir y ejecutar los contenedores:

docker-compose up --build
