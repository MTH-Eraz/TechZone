<div align="center">

# 🛒 Techzone
### Simple PHP & MySQL Based E-Commerce Web Application

Techzone is a beginner-friendly online shopping system built using **PHP** and **MySQL**.  
It allows users to browse products, create accounts, log in, and manage a shopping cart.  
The system also provides a basic **admin panel** for managing products and customer records.

![PHP](https://img.shields.io/badge/PHP-Backend-blueviolet?style=for-the-badge&logo=php)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge&logo=mysql)
![HTML](https://img.shields.io/badge/HTML-Markup-orange?style=for-the-badge&logo=html5)
![CSS](https://img.shields.io/badge/CSS-Styling-1572B6?style=for-the-badge&logo=css3)

</div>

---

## 📌 Project Overview

**Techzone** is a simple e-commerce web application designed to demonstrate the core concepts of **web development using PHP and MySQL**.

The system simulates a basic online shopping platform where users can explore products, register accounts, and manage a shopping cart. The project also includes an admin interface to control product listings.

This project is mainly intended for **learning purposes**, especially for students who want to understand how an e-commerce system works internally.

---

## 🚀 Key Features

### 👤 Customer Features
- User Registration System
- Secure Login System
- Product Browsing
- Add Products to Cart
- Remove Products from Cart
- Session-Based Cart Management

### 🧑‍💼 Admin Features
- Admin Product Management
- Customer Record Viewing
- Database-Controlled Product System

---

## 🗂️ Project Structure

```
Techzone/
│
├── admin/            # Admin panel related files
├── customer/         # Customer interface pages
├── pimg/             # Product images
├── Screenshots/      # Website screenshots
│
├── Cart.php          # Cart management logic
├── connection.php    # Database connection configuration
├── explore.php       # Product listing page
├── index.php         # Homepage
├── login.php         # Login page
├── SignUp.php        # Registration page
├── nav.php           # Navigation bar component
├── footer.php        # Footer component
│
└── README.md         # Project documentation
```

---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository

```
git clone https://github.com/iftikhoq/Techzone.git
```

---

### 2️⃣ Create Database

Open **phpMyAdmin** and create a new database named:

```
techzone
```

Import the SQL file if it is available, or manually create the required tables.

---

### 3️⃣ Configure Database Connection

Open the file **connection.php** and update the database configuration.

```php
$con = mysqli_connect("localhost","username","password","database_name");
```

Example:

```php
$con = mysqli_connect("localhost","root","","techzone");
```

---

### 4️⃣ Run the Project

Move the project folder to:

For **XAMPP**

```
htdocs/
```

For **WAMP**

```
www/
```

Then start **Apache** and **MySQL**.

Open your browser and visit:

```
http://localhost/Techzone/
```

---

## 📸 Screenshots

### Homepage
![Homepage](Screenshots/Picture1.png)

### Signup Page
![Signup](Screenshots/Picture2.png)

### Shopping Cart
![Shopping Cart](Screenshots/Picture3.png)

### Customer Records
![Customer Record](Screenshots/Customer_record.png)

---

## 🛠️ Technologies Used

The system was developed using the following technologies:

- **PHP** – Backend programming
- **MySQL** – Database management
- **HTML** – Web page structure
- **CSS** – Styling and layout
- **PHP Sessions** – Cart and login handling

---

## 🔮 Future Improvements

Possible future enhancements for this project include:

- 🔍 Product search and filtering system
- 💳 Payment gateway integration
- 📦 Order history and checkout system
- 📱 Fully responsive UI using Bootstrap or Tailwind
- 🔐 Password hashing and security improvements

---

## 📄 License

This project is open-source and can be freely used for **learning and educational purposes**.

---

## 👨‍💻 Author

**Tamjidul Hasan**

GitHub Profile:  
https://github.com/MTH-Eraz
