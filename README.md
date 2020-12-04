# **Docker php Telfy**

## Proyecto base para la configuracion de un entorno de desarrollo para PHP.

### Crear el archivo .env
```sh
$ cp .env.example .env
```
### Configurar las diferentes opciones
PHP_VERSION=7.4
NGINX_PORT=8081
MYSQL_PORT=3307
MYSQL_DATABASE=ispges
MYSQL_ROOT_PASSWORD=Cambiar1234
MYSQL_PASSWORD=Cambiar1234

### Construir los contenedores
```sh
$ docker-compose build
```

### Arrancar los contenedores y disfrutar
```sh
$ docker-compose up -d
```
