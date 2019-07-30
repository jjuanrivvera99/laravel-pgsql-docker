<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Description

[This](https://github.com/jjuanrivvera99/laravel-pgsql-docker) is a laravel 5.8, PostgreSQL and pgAdmin4 project with docker-compose.

## How to run this project

To run this project you need to have docker and docker-compose installed in your machine.

Take the following steps:

- clone this repository by executing the following command: 'git clone https://github.com/jjuanrivvera99/laravel-pgsql-docker'
- change directory: 'cd laravel-pgsql-docker'
- run command: 'docker-compose up -d'
- run command: 'docker exec -it laravel bash'
- run command: 'composer install'
- create a '.env' file
- run command: 'php artisan key:generate'
- run command: 'chmod 777 -R storage bootstrap public'

Optionally commnads

- php artisan make:auth
- php artisan config:cache
- php artisan migrate

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
