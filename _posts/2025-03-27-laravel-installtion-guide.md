---
layout: post
title: Laravel Installation Guide
subtitle: Step-by-step guide to installing Laravel
categories: Laravel
tags: [installation, Laravel, guide]
top: 1
new: 1
banner: 
  image: 'data:image/webp;base64,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'
sidebar: []
---

This guide walks you through installing [Laravel][1] step by step.

## Laravel Installation Guide

*Note: This guide assumes you have basic knowledge of PHP and Composer.*

## Prerequisites

Before installing Laravel, ensure you have the following:

- **PHP (>= 8.0)** – Laravel requires PHP 8.0 or higher.
- **Composer** – Laravel uses Composer to manage dependencies.
- **Web Server** – Apache or Nginx.
- **Database** – MySQL, PostgreSQL, SQLite, or SQL Server.

## Installing Laravel

### Using Composer

Run the following command in your terminal:

```sh
composer create-project --prefer-dist laravel/laravel my-laravel-app
```

This command installs Laravel in a new directory called `my-laravel-app`.

### Verifying Installation

Navigate into your project folder:

```sh
cd my-laravel-app
```

Start the local development server:

```sh
php artisan serve
```

Open `http://127.0.0.1:8000` in your browser. If you see the Laravel welcome page, your installation is successful.

## Configuring Environment

Laravel uses an `.env` file for environment configuration. Copy the example file:

```sh
cp .env.example .env
```

Then generate an application key:

```sh
php artisan key:generate
```

## Database Configuration

Update your `.env` file with database details:

```ini
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

Run migrations to set up the database:

```sh
php artisan migrate
```

## Running Your Laravel Application

Use the built-in PHP server:

```sh
php artisan serve
```

Or configure a virtual host in Apache/Nginx for better performance.

## Conclusion

You have successfully installed Laravel! Explore the framework and build amazing applications.

For more details, visit the official [Laravel documentation][2].

---

## Additional Resources

- [Laravel Documentation][2]
- [Composer Documentation][3]
- [PHP Official Site][4]

[1]: https://laravel.com/
[2]: https://laravel.com/docs
[3]: https://getcomposer.org/doc/
[4]: https://www.php.net/
