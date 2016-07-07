# Docker Image and Container php-apache & mysql

## Contenido de este repositorio

* `Base` El SO utilizado para esta demostracion es Ubuntu Server LTS X64

* `Instalación` Se descargan los archivos contenidos es esta carpeta y se ejecutan los siguientes comandos.
```c
$ docker-compose build
$ docker-compose up -d
```
* `Instalación opcional` Instalacion sin necesidad de descargar los archivos contenidos en esta carpeta
```c
$ docker pull php:5.6-apache ó docker build
$ docker run -d -p 81:80 3301:3306 --name name-container -v "$PWD":/var/www/html php:5.6-apache -e MYSQL_ROOT_PASSWORD=123456 -d mysql:5.7
```
* `Captura de pantalla` 

##### Prueba apache
![alt tag](https://docs.google.com/drawings/d/1dEQl2bB06Jlr6nDXCndcWYLcpSzJr5Knyhg28d_xBgk/pub?w=352&h=137)
##### Prueba php_info()
![alt tag](https://docs.google.com/drawings/d/1JKVO8UQ2f6lQih5HEiwHPxzOxS7dYeZuHIxWr0vVB-E/pub?w=960&h=590)
##### Prueba html
![alt tag](https://docs.google.com/drawings/d/1r722K18Xg_xxOvh0K2U-UgEcFCQJpiUv8WXEikrK6cY/pub?w=341&h=192)
##### Prueba shell_exec
![alt tag](https://docs.google.com/drawings/d/1LlpTn0zEqjroZ1GqlMZ1v2pxjFbxhA57uMrBkXXe3BY/pub?w=418&h=167)
