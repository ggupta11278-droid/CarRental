# 🚗 Car Rental Management System

A web-based Car Rental Management System that allows users to explore available cars and manage car rental operations through a PHP and MySQL-based application.

## 📌 Project Overview

The Car Rental Management System is designed to simplify the process of renting cars online. It provides a web interface for browsing cars, managing user accounts, and handling rental-related operations.

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript, jQuery
- **Backend:** PHP
- **Database:** MySQL
- **Web Server:** Apache (XAMPP)

## 📂 Project Structure

```text
CarRental/
│
├── admin/          # Admin-related files
├── css/            # Stylesheets
├── db/             # Database files
├── fonts/          # Font resources
├── img/            # Images and assets
├── includes/       # PHP configuration and common files
├── js/             # JavaScript files
│
├── index.php       # Main website page
├── login.php       # User login
├── signup.php      # User registration
└── account.php     # User account
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Move Project to XAMPP

Copy the project folder into:

```text
C:\xampp\htdocs\
```

### 3. Start XAMPP

Start the following services:
- Apache
- MySQL

### 4. Create the Database

1. Open `http://localhost/phpmyadmin/`.
2. Create a database named `cars`.
3. Select the database.
4. Go to the Import tab.
5. Import the `db/cars.sql` file.

### 5. Configure Database Connection

Open:

```text
includes/config.php
```

Configure the database host, username, password, and database name according to your local MySQL setup.

### 6. Run the Application

Open your browser and visit:

```text
http://localhost/CarRental/
```

## ✨ Key Components

- User authentication
- Car rental management
- Database-driven application
- Admin-related functionality
- User account management

## 📄 License

Govind Gupta
