## Invoice Management System

<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fmybillbook.in%2Fs%2Finvoice-management-system%2F&psig=AOvVaw0Yzg6sE23STlHpHaQ677P7&ust=1762698112293000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCLikq6rg4pADFQAAAAAdAAAAABAL">

**Created By :**  Mohammed Shaaban
**Email :** dev.mohammed.shaaban@gmail.com


Key Features:
- Invoice Creation: Users can add new invoices by specifying essential details such as invoice number, amount, customer name, and date.

- Invoice Management: A dashboard allows users to view all invoices in a table format, with options to search, filter, and paginate the list.

- CRUD Operations: Fully implemented Create, Read, Update, and Delete (CRUD) functionality for managing invoices.

- User Authentication: integrated user login and authentication to ensure secure access to invoice date.

- Database Management: Designed and implemented a MySQL database schema to store invoices and user data efficiently.

- Responsive UI: Used Bootstrap and JavaScript to create a simple, responsive user interface, making it easy to manage invoices on both desktop and mobile devices.



## Installation

To get started, clone this repository.

```
git clone https://github.com/mohammedshaaban1/Invoices-Laravel-10.git
```

Next, copy your `.env.example` file as `.env` and configure your Database connection.

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=YOUR-DATABASE-NAME
DB_USERNAME=YOUR-DATABASE-USERNAME
DB_PASSWORD=YOUR-DATABASE-PASSWROD
```

## Run Packages and helpers

You have to all used packages and load helpers as below.

```
composer install
npm install
npm run build
```

## Generate new application key

You have to generate new application key as below.

```
php artisan key:generate
```

## Run Migrations and Seeders

You have to run all the migration files included with the project and also run seeders as below.

```
php artisan migrate
```
