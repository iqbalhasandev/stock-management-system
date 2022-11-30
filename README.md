<p align="center">
    <h1 align="center">POS System Using Laravel</h1>
</p>

## Installation

### Requirements

For system requirements you [Check Laravel Requirement](https://laravel.com/docs/9.x/deployment#server-requirements)

### Clone the repository from github.

    git clone https://github.com/iqbalhasandev/laravel-pos.git [YourDirectoryName]

The command installs the project in a directory named `YourDirectoryName`. You can choose a different
directory name if you want.

### Install dependencies

Laravel utilizes [Composer](https://getcomposer.org/) to manage its dependencies. So, before using Laravel, make sure you have Composer installed on your machine.

    cd YourDirectoryName
    composer install

### Config file

Rename or copy `.env.example` file to `.env` 1.`php artisan key:generate` to generate app key.

1. Set your database credentials in your `.env` file
1. Set your `APP_URL` in your `.env` file.

### Database

1. Migrate database table `php artisan migrate`
1. `php artisan db:seed`, this will initialize settings and create and admin user for you [email: admin@gmail.com - password: admin123]

### Install Node Dependencies

1. `npm install` to install node dependencies
1. `npm run dev` for development or `npm run build` for production

### Create storage link

`php artisan storage:link`

### Run Server

1. `php artisan serve` or Laravel Homestead
1. Visit `localhost:8000` in your browser. Email: `admin@gmail.com`, Password: `admin123`.

### Screenshots

#### Product list

![Product list](https://raw.githubusercontent.com/iqbalhasandev/laravel-pos/master/screenshots/products_list.png)

#### Create order

![Create order](https://raw.githubusercontent.com/iqbalhasandev/laravel-pos/master/screenshots/pos.png)

#### Order list

![Order list](https://raw.githubusercontent.com/iqbalhasandev/laravel-pos/master/screenshots/order_list.png)

#### Customer list

![Customer list](https://raw.githubusercontent.com/iqbalhasandev/laravel-pos/master/screenshots/customer_list.png)
