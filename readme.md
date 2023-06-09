# Laravel Vuetify SPA Starter
Starter SPA built with Laravel 6.0, JWT Auth, Vue 2, Vue Router 3, Vuex 3, Axios, Vuetify 2

## Included
* [Laravel 6.0](https://laravel.com/docs/6.0)
* [Vue 2](https://vuejs.org)
* [Vue Router 3](http://router.vuejs.org)
* [Vuex 3](http://vuex.vuejs.org)
* [Axios](https://github.com/mzabriskie/axios)
* [Authentication with JWT Token](https://github.com/tymondesigns/jwt-auth)
* [Vuetify](https://vuetifyjs.com/en/getting-started/quick-start)

## Installation:
* Clone the repo
* Copy `.env.example` to `.env`
* Configure `.env`
* Run `composer install`
* Run `php artisan key:generate`
* Run `php artisan jwt:secret`
* Run `php artisan db:create`
* Run `php artisan migrate:refresh --seed`
* Run `npm install`
* Make sure `storage/framework/cache`, `storage/framework/sessions`, `storage/framework/views` directories exist. Run `mkdir -p storage/framework/{sessions,views,cache}`

<!-- ## It need to excute sql files in sql directory. -->

## Usage
* Run `php artisan serve` for running laravel backend
* Run `npm run watch` for live reloading using BrowserSync
* Run `npm run hot` for hot reloading
* Run `npm run prod` for production buid