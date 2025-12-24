# Database Systems

This is the final project for the NDHU CSIEB0290 Database Systems (2024 Spring) course. 

## Online Bookstore Management System

### Overview
This project is a comprehensive web-based management system for an online bookstore. It is designed to provide users with a seamless shopping experience and administrators with robust tools for inventory and order management.

### How to Run

#### 1. Requirements
Before running the application, ensure you have a web server environment (such as XAMPP or WAMP) with the following components:
* PHP (7.0 or higher recommended)
* MySQL Database
* Apache Server

#### 2. Database Configuration
1.  Create a MySQL database named `OnlineBookstore`.
2.  Set up the following tables based on the schema provided in the project report:
    * `User`: To store customer details.
    * `Book`: To store inventory information.
    * `Order`: To track purchase transactions.
    * `OrderItem`: To store details of books within each order.
    * `Admin`: To store administrator credentials.
3.  Update the database connection parameters (host, username, password, and port) in the PHP files to match your local environment.

#### 3. Running the Web App
1.  Place the project folder in your server's root directory (e.g., `htdocs` for XAMPP).
2.  Start the Apache and MySQL modules in your server control panel.
3.  Open your web browser and navigate to:
```
http://localhost/your-project-folder/index.php
```

### Data Source
The book data used in this project was sourced from [Books.com.tw (博客來外文書)](https://www.books.com.tw/).