# LARAVEL PULSE

This project intended to learn and try laravel pulse as monitoring system for laravel

## Laravel Framework
Laravel Pulse only available on laravel 10++ and PHP 8.1++

## How to install pulse ?
> 1. `composer require laravel/pulse`
> 2. `php artisan vendor:publish --provider="Laravel\Pulse\PulseServiceProvider"`
> 3. `php artisan migrate`

## How can i change database only for pulse purpose so its not on main app database ?
Sure, For high-traffic applications, you may prefer to use a dedicated database connection for Pulse to avoid impacting your application database.

You may customize the database connection used by Pulse by setting the PULSE_DB_CONNECTION environment variable.
`PULSE_DB_CONNECTION=pulse`
