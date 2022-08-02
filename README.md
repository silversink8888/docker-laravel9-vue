# docker-laravel 🐳

![License](https://img.shields.io/github/license/ucan-lab/docker-laravel?color=f05340)

## Introduction

Build a simple laravel development environment with docker-compose.

## software

docker
PHP:7.4
laravel:8.5
Mysql:5.7
phpmyadmin:5
Vue.js:

## Usage

```bash
$ git clone https://github.com/silversink8888/docker-laravel-vue.git
$ cd docker-laravel-vue
$ docker-compose build
$ docker-compose up -d
$ docker-compose exec php bash
$ composer create-project --prefer-dist laravel/laravel laravel "8.*"
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


