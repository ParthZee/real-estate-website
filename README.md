# Real Estate Website

## Project Overview

This real estate website allows users to browse, search, and manage property listings. Registered users can post properties for sale or rent, save favorite listings, and manage their submissions. Admins can oversee all activity, moderate content, and manage user interactions. The platform serves as a basic property marketplace enabling interactions between property owners and potential buyers or renters.

This is a complete real estate listing website built using **HTML**, **CSS**, **JavaScript**, **PHP**, and **MySQL**. The project includes user authentication, property posting, and an admin dashboard to manage listings and users.

## Features

### User Functionality

- Register and login as a user
- Search properties (`search.php`)
- View property listings (`listings.php`, `view_property.php`)
- Post properties (`post_property.php`)
- Save properties to favorites (`saved.php`)
- Manage personal listings (`my_listings.php`, `update_property.php`)

### Admin Functionality

- Admin login (`admin/login.php`)
- View dashboard (`admin/dashboard.php`)
- Manage property listings (`admin/listings.php`)
- Manage messages, requests, and user accounts (`admin/messages.php`, `admin/admins.php`)

## Project Structure

> **Note**: Image files and folders (e.g., `images/`, `uploads/`, `.jpg`, `.png`) are intentionally excluded from this overview for clarity.

```plaintext
real-estate-website/
├── about.php
├── contact.php
├── dashboard.php
├── home.php
├── login.php
├── register.php
├── post_property.php
├── listings.php
├── my_listings.php
├── saved.php
├── search.php
├── update.php
├── update_property.php
├── view_property.php
└── admin/
    ├── admins.php
    ├── dashboard.php
    ├── listings.php
    ├── login.php
    └── messages.php
```

## Database

The project uses a MySQL database. You should import the provided SQL file `home_db.sql` into your MySQL server. Update the database connection parameters in your PHP files as needed (typically in a config or connection file).

## Setup Instructions

1. Clone or extract the project to your web server directory (e.g., `htdocs` for XAMPP).
2. Create a MySQL database and import the SQL schema.
3. Configure database credentials in your PHP files.
4. Launch the site via `localhost/real-estate-website`.

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL