<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

Step for creating this template in laravel 10 :

    Create a new Laravel 10.x project composer create-project laravel/laravel:^10 your-project-name*
    Install the needed package composer require laravel/ui
    Apply the new auth scaffolding using bootstrap and laravel/ui: php artisan ui bootstrap --auth
    Run npm i and
    Configure correctly the .env file
    Run php artisan migrate
    Run on two separeted terminals:
        run npm run dev to build iteratively our front-end packages and code
        run php artisan serve to build iteratively our back-end packages and code
    Start changing the world with your oustanding code!

Step for using the template : 


    Copy and paste the .env.example file and rename it into .env without removing the env.example file
    Run composer install to install all our composer packages
    Run php artisan key:generate to generate our custom application key
    Run npm i to install all our npm packages
    Run on two separeted terminals:
        run npm run dev to build iteratively our front-end packages and code
        run php artisan serve to build iteratively our back-end packages and code
    Start changing the world with your oustanding code!
