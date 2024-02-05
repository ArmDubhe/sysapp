# sysapp

Installation
```sh
composer install
```
Configuration

```sh
cp .env.example .env 

php artisan key:generate

php artisan serve
```
Get and install the
[debugger bar](https://packagist.org/packages/barryvdh/laravel-debugbar)



DB

```sh
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```