<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

## Installation
### First clone or download this repository
```shell
git clone https://github.com/denisuryadi26/inertia-pos.git
```

After clone or download this repository, next step is install all dependency required by laravel and laravel-mix.

```shell
# install composer-dependency
composer install
npm install
```

### Next Step
Before we start web server make sure we already generate app key, configure `.env` file and do migration.

```shell
# create copy of .env
cp .env.example .env

# create laravel key
php artisan key:generate
# config database user and password

# migrate & seed some data
php artisan migrate:fresh --seed

#ready to serve
php artisan serve
```

### Default User
Role Administrator
Email : admin@gmail.com <br>
Password  : password

Role Kasir
Email : kasir@gmail.com <br>
Password  : password

```
Thank you for considering contributing to this repo!

## Contributing
Thank you for considering contributing to this repo!
