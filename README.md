## Installation
```
composer create-project laravel/laravel TALL-Course
composer require livewire/livewire
composer require laravel/breeze
```
## Implementation
Using Model, controllers, migrations and seeders to create a component. Eg-
```
php artisan make:model Subscriber -mfc
php artisan breeze:install (For Login,Register,ForgotPassword functionality)
```
## Setup
```
php artisan migrate:fresh --seed
```
