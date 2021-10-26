<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
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

## STEP 
Buka terminal kalian pastikan sudah menginstall Laravel 

 - cara install laravel <a href="https://laravel.com/docs/8.x">Install laravel</a>

Pertama tama buat project laravel baru kalian di dalam folder htdocs jika menggunakan xampp

```
Laravel new Nama-project-kalian
```

Pindah ke folder tersebut dengan 

```
cd Nama-project-kalian
```

Installing Jetstream di dalam folder project kalian, Pastikan sudah menginstall composer

```
composer require laravel/jetstream
```
next install livewire dengan jetstream

```
php artisan jetstream:install livewire
```

Kemudian setelah menginstal Jetstream, Kalian harus menginstal dan membangun dependensi NPM pastikan sudah menginstall node js 

 - cara install Node js <a href="https://nodejs.org/en/download/">Node Js</a>

```
npm install && npm run dev

```


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
