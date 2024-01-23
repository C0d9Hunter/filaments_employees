# create project

### create laravel project
composer create-project laravel/laravel

### install breeze
composer require laravel/breeze --dev
php artisan breeze:install
php artisan migrate

### install filament (attention il y'a une version 3)
composer require filament/filament:"^2.0"

php artisan make:filament-user


# Create Github repo

### create github repo

### Fix login attempt
#### Authentification
[-] User will be able to login with email and password
[-] Three (3) failed attempt will lock the user for 5 min


### Create model and migrations