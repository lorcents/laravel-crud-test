<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>


## BASIC CRUD WITH LARAVEL
### You will need 
- composer
- laravel
- npm
- mysql,php



## Setup Guide
Step 1: Clone this project
```
git clone https://github.com/lorcents/laravel-crud-test.git
```

Step 2: Install project dependencies using composer.
```
composer install
```

Step 3: Install project dependencies using npm.
```
npm install
```

Step 4: move .env.example file to .env file.
```
mv .env.example .env
```
Step 5: Generate encryption key using below command
```
php artisan key:generate
```

Step 6: Create databse laravel-crud.Configure your database credentials in .env file.
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel-crud
DB_USERNAME=root
DB_PASSWORD=
```

Step 7: Run artisan migration command to migrate table.
```
php artisan migrate
```

Step 8: Run artisan serve command to start app server.
```
php artisan serve
```




