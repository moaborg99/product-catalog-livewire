# Product Catalog – Laravel Livewire

A fictional product catalog built during my LIA internship.

This project is one of three separate implementations of the same application, created to compare different frontend approaches within the Laravel ecosystem.

## Purpose

The goal of this project was to explore and compare:

- Developer experience
- Component architecture
- State handling
- Routing and rendering patterns
- Overall workflow in Laravel applications

This version was built using Laravel Livewire for a more server-driven frontend experience.

## Tech Stack

- Laravel
- Livewire
- Tailwind CSS
- SQLite

## Features

- Product listing
- Product detail pages
- Filtering and search
- Responsive UI
- Component-based structure

## Setup

```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
touch database/database.sqlite
php artisan migrate --seed
npm run dev
php artisan serve
```

## Notes

This project was published with permission for portfolio purposes.

Part of a comparison project alongside:

- Inertia.js + Vue
- Inertia.js + React
