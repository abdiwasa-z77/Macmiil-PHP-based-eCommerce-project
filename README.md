# PHP eCommerce Website

A simple PHP-based eCommerce project built with a classic PHP page structure and admin dashboard.

## Overview

This eCommerce website includes customer-facing pages for browsing products, categories, cart management, checkout, and order tracking. It also includes an admin panel for managing products, categories, orders, customers, shipping, and site content.

## Features

- Product listings and product details
- Category navigation (top, mid, end categories)
- Shopping cart and checkout flow
- Customer registration, login, and profile management
- Order history and tracking for customers
- Admin panel with product, category, order, and customer management
- CRUD management for colors, sizes, shipping costs, sliders, FAQs, and settings

## Recommended Environment

- PHP 5.6 or PHP 7.4
- MySQL / MariaDB database
- Apache or compatible web server

## Database

- Database name: `ecommerceweb`

The database is expected to be imported from the provided SQL dump or setup file in the repository if available.

## Installation

1. Copy the project files into your web server document root.
2. Create the MySQL database `ecommerceweb`.
3. Import the database schema and data from the provided SQL file (if available).
4. Update the database connection settings in the project if needed.
5. Open the website in your browser and navigate to the home page.

## Admin Login

- Email: `admin@mail.com`
- Password: `Password@123`

## Important Notes

- Customer verification may require directly updating the `active` status in the database.
- This project appears to be developed by `Abdiwasa Abdilahi`.

## Project Structure

- `index.php` - Main front-end landing page
- `product.php`, `product-category.php`, `search-result.php` - Product browsing pages
- `cart.php`, `checkout.php`, `payment_success.php` - Shopping and checkout flow
- `login.php`, `registration.php`, `customer-*` pages - Customer account management
- `admin/` - Admin panel for managing site content and orders

## License

This repository does not include explicit licensing information. Use and modify it according to the original source's terms.
