# 🛒 Techzone – PHP Based E-Commerce Website

**Techzone** is a beginner-level e-commerce web application developed using **PHP** and **MySQL**.  
The system allows users to browse available products, create accounts, log in, and manage a shopping cart. It also includes a basic **admin dashboard** that enables administrators to control product information.

The purpose of this project is to demonstrate the fundamental concepts of **web development, database connectivity, user authentication, and session-based cart systems**.

---

# 📌 About the Project

Techzone simulates a simple **online shopping environment** where customers can explore products and add them to their cart before making purchasing decisions.

The application is organized into two main sections:

### Customer Section
- User registration and login
- Viewing available products
- Managing shopping cart items

### Admin Section
- Managing product listings
- Viewing customer information

This project is mainly intended for **students and beginners** who want to understand how a basic e-commerce website works using **PHP and MySQL**.

---

# 🚀 Main Features

- 👤 User account registration and login system
- 🛍️ Product browsing interface
- 🛒 Add products to cart
- ❌ Remove items from cart
- 🔄 Session-based cart handling
- 🧑‍💼 Admin panel for product management
- 💾 Product data stored in a MySQL database

---

# 📂 Project Directory Structure

```
Techzone/
│
├── admin/            # Admin related pages and controls
├── customer/         # Pages accessible to customers
├── pimg/             # Product image storage
├── Screenshots/      # Website preview images
│
├── Cart.php          # Handles shopping cart operations
├── connection.php    # Database connection setup
├── explore.php       # Displays available products
├── index.php         # Homepage of the website
├── login.php         # User login interface
├── SignUp.php        # User registration page
├── nav.php           # Navigation bar component
├── footer.php        # Footer component
│
└── README.md         # Project documentation
```

---

# ⚙️ Setup and Installation

## 1️⃣ Clone the Repository

Run the following command to download the project:

```
git clone https://github.com/iftikhoq/Techzone.git
```

---

## 2️⃣ Create the Database

1. Open **phpMyAdmin**
2. Create a database named:

```
techzone
```

3. Import the provided **SQL file** if available  
   or manually create the necessary tables.

---

## 3️⃣ Configure Database Connection

Open the file **connection.php** and modify the database credentials:

```php
$con = mysqli_connect("localhost","username","password","database_name");
```

Example configuration:

```php
$con = mysqli_connect("localhost","root","","techzone");
```

---

## 4️⃣ Run the Application

1. Move the project folder into:

For **XAMPP**

```
htdocs/
```

For **WAMP**

```
www/
```

2. Start **Apache** and **MySQL**

3. Open your browser and go to:

```
http://localhost/Techzone/
```

---

# 📸 Screenshots

### Homepage
![Homepage](Screenshots/Picture1.png)

### Signup Page
![Signup](Screenshots/Picture2.png)

### Shopping Cart
![Shopping Cart](Screenshots/Picture3.png)

### Customer Records
![Customer Record](Screenshots/Customer_record.png)

---

# 🛠️ Technologies Used

The project is built using the following technologies:

- **PHP** – Backend logic
- **MySQL** – Database management
- **HTML** – Page structure
- **CSS** – Styling
- **PHP Sessions** – Cart management

---

# 🔮 Possible Future Enhancements

Some improvements that could be added in the future include:

- 🔍 Product search and filtering system
- 💳 Online payment gateway integration
- 📦 Order history tracking
- 📱 Fully responsive UI using Bootstrap or Tailwind
- 🔐 Password hashing and enhanced security features

---

# 📄 License

This project is open-source and mainly created for **learning and educational purposes**.

---

# 👨‍💻 Developer

**Tamjidul Hasan**

GitHub Profile:  
https://github.com/MTH-Eraz
