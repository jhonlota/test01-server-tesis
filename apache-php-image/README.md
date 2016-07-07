# Docker Image and Container php-apache & mysql

## Contenido de este repositorio

* `Base` El SO utilizado para esta demostracion es Ubuntu Server LTS X64

* `Instalación` Se descargan los archivos contenidos es esta carpeta y se ejecutan los siguientes comandos.

$ docker-compose build
$ docker-compose up -d

* `Instalación opcional` Instalacion sin necesidad de descargar los archivos contenidos en esta carpeta

$ docker pull php:5.6-apache ó docker build
$ docker run -d -p 81:80 3301:3306 --name name-container -v "$PWD":/var/www/html php:5.6-apache -e MYSQL_ROOT_PASSWORD=123456 -d mysql:5.7

* `Captura de pantalla` 
## Prueba apache
![alt tag](https://docs.google.com/drawings/d/1dEQl2bB06Jlr6nDXCndcWYLcpSzJr5Knyhg28d_xBgk/pub?w=352&h=137)
