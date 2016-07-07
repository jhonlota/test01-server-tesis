# Docker Image and Container

## Contenido de este repositorio
* `Enlaces` 

[Presentación](https://docs.google.com/presentation/d/1uyyC_uwKlR9I28dycw7c0DT78APXoa4BdhJuZs_e3To/edit?usp=sharing)

[Video bash](https://asciinema.org/a/d6z23b0zixexiw49htorpwmke)
* `Base` El SO utilizado para esta demostracion es Ubuntu Server LTS X64

* `Instalación docker`
```c
$ sudo apt-get update
$ wget -qO- https://get.docker.com/ | sh

```
* `Instalación docker-compose`
```c
$ curl -L https://github.com/docker/compose/releases/download/1.6.2/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
$ chmod +x /usr/local/bin/docker-compose
```
