# docker-laravel 🐳

![License](https://img.shields.io/github/license/ucan-lab/docker-laravel?color=f05340)

## Introduction

Build a simple laravel development environment with docker-compose.

## software

docker
PHP:8.1
laravel:9.2
Mysql:5.7
phpmyadmin:5
Vue.js:3.2.37

## Usage

```bash
$ git clone https://github.com/silversink8888/docker-laravel9-vue.git
$ cd docker-laravel9-vue
$ docker-compose build
$ docker-compose up -d
$ docker-compose exec php bash
$ laravel new laravel_jetstream --jet
$ mv laravel_jetstream laravel
$ chmod -R 777 laravel/storage
$ cd laravel
$ php artisan migrate
```

laravel
http://localhost:8080/

phpmyadmin
http://localhost:8888/


## Container structures

```bash
├── mysql
├── nginx
├── php
└── server
```


