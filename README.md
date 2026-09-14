# POS System (Version 1)

## Overview

This project is a basic Point-of-Sale (POS) System developed using CodeIgniter 4. It demonstrates the Model-View-Controller (MVC) architecture by implementing multiple pages, routing, controllers, and views.

The application currently uses static PHP arrays as temporary data sources for customer and user account information. No database integration has been implemented yet.

## Features

- Landing Page (/)
- About Page (/about)
- Customer Accounts Page (/customers)
- User Accounts Page (/users)
- Navigation between all pages
- Dynamic data display using PHP foreach loops
- Built with CodeIgniter 4

## Technologies Used

- PHP 8+
- CodeIgniter 4
- HTML5
- CSS3
- Composer

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/suhnshaine/pos-system.git
```

### 2. Navigate to the Project Folder

```bash
cd pos-system
```

### 3. Install Dependencies

```bash
composer install
```

### 4. Start the Development Server

```bash
php spark serve
```

### 5. Open the Application

Visit:

```text
http://localhost:8080
```

## Available Routes

| Route | Description |
|---------|-------------|
| / | Landing Page |
| /about | About Page |
| /customers | Customer Accounts |
| /users | User Accounts |

## Project Structure

```text
app
├── Controllers
│   ├── Pages.php
│   ├── Customers.php
│   └── Users.php
│
├── Views
│   ├── home.php
│   ├── about.php
│   ├── customers.php
│   └── users.php
│
└── Config
    └── Routes.php
```

## Sample Data

### Customer Accounts

The Customer Accounts page displays customer records containing:

- Full Name
- Email Address
- Phone Number

### User Accounts

The User Accounts page displays user records containing:

- Username
- Full Name
- Role

## Author

**SHIREALETH ACORDA**

Student, FEU Institute of Technology

## License

This project was created for academic purposes.

## Live Demo

https://posscacorda.infinityfreeapp.com
