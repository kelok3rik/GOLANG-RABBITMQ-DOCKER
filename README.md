# Ejemplo de Colas con Go y RabbitMQ en Docker

Este proyecto proporciona un ejemplo básico de cómo usar RabbitMQ con Go para implementar colas de mensajes. La configuración utiliza Docker para levantar un contenedor de RabbitMQ y ejecutar los scripts de productor y consumidor en Go.

### Requisitos Previos

- Docker: Asegúrate de tener Docker instalado en tu máquina. Instalar Docker
- Go (Golang): Asegúrate de tener Go instalado para compilar y ejecutar los scripts. Instalar Go

### Configuración
Clonar el Repositorio
Clona este repositorio en tu máquina local:


- *git clone https://github.com/kelok3rik/GOLANG-RABBITMQ-DOCKER*



- Crea una red Docker personalizada llamada rabbitmq-cluster:

     *docker network create rabbitmq-cluster* 

- Levantar el Contenedor de RabbitMQ

    *docker-compose up -d*
