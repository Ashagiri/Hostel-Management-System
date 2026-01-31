# Hostel-Management-System

# 📌 Project Overview:
The Hostel Management System is a web-based application designed to manage hostel operations efficiently.
It helps administrators handle student records, room allocation, warden details, payments, and other hostel-related activities in a centralized and organized manner.
This project aims to reduce manual work, improve data accuracy, and provide an easy-to-use interface for hostel management.

# 👥 Team Members:
Asha Giri

Komal Basnet

Gagan Prasai

Jitendra Narayan Raut

# 🎯 Objectives:
To automate hostel management tasks

To manage student, room, warden, and payment records efficiently

To provide a secure admin login system

To store and retrieve data using a database

To improve accuracy and reduce paperwork

# ⚙️ Features:
Admin Login & Logout System

Student Management (Add, Update, Delete, View)

Room Management

Warden Management

Payment Management

Dashboard with hostel statistics

Database connectivity

User-friendly interface

# 🛠️ Built With
Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Server: Apache (XAMPP / WAMP)

# ⚙️ How to Run
Follow these steps to set up and run the project locally using XAMPP or WAMP:
## 1. Prerequisites
* Install XAMPP or WAMP.

A web browser (Chrome, Firefox, etc.).

## 2. Project Setup
Download/Clone the Repository: * Clone this repo or download the ZIP file.

Move the project folder into your server's local directory:

XAMPP: C:/xampp/htdocs/Hostel-Management-System

WAMP: C:/wamp64/www/Hostel-Management-System

## 3. Database Configuration
Start Apache and MySQL from your XAMPP/WAMP Control Panel.
Open your browser and go to http://localhost/phpmyadmin/.
Create a new database named hostel_db (or the name specified in your config file).

Import the SQL file: Look for a .sql file in the project folder, click the Import tab in phpMyAdmin, and upload it to populate the tables.

## 4. Configure Connection
Open the database connection file (usually config.php or db_connect.php) in your code editor.

Ensure the credentials match your local setup:

PHP
$servername = "localhost";
$username = "root";
$password = ""; // Default is empty for XAMPP
$dbname = "hostel_db";


## 5. Launch the Application
In your browser, navigate to: http://localhost/Hostel-Management-System/index.php


# 📂 Repository Structure
📂 Repository Structure
Hostel-Management-System/ │ ├── admin/ # Admin dashboard files │ ├── dashboard.php │ ├── profile.php │ └── logout.php │ ├── student/ # Student management modules │ ├── add_student.php │ ├── view_student.php │ └── update_student.php │ ├── warden/ # Warden management modules │ ├── add_warden.php │ └── view_warden.php │ ├── room/ # Room management modules │ ├── add_room.php │ └── view_room.php │ ├── payment/ # Payment management modules │ ├── add_payment.php │ └── view_payment.php │ ├── images/ # Images and output screenshots │ ├── login.png │ ├── dashboard.png │ └── output.png │ ├── css/ # CSS files │ └── style.css │ ├── js/ # JavaScript files │ └── script.js │ ├── database/ # Database files │ └── hostel_db.sql │ ├── index.php # Main entry file ├── config.php # Database configuration └── README.md # Project documentation

# Testing:
Test ID,Feature,Description,Expected Result,Status
TC-01,Root Redirect,Open main GitHub Pages URL.,Automatically redirects to home.html.,✅ Pass
TC-02,Admin Login,Enter correct credentials in adminlogin.html.,Redirects to admin_dashboard.html.,✅ Pass
TC-03,Registration,Submit the form in registration.html.,Data is captured and success message appears.,✅ Pass
TC-04,Navigation,"Click ""About"" link on the home page.",Loads abouthostel.html correctly.,✅ Pass


# 🎓 Conclusion:
In conclusion, the Hostel Management System successfully transitions hostel administration from manual, paper-based processes to a streamlined digital environment. By centralizing student records, room allocations, and payment tracking into a single web-based application, the system achieves its primary objective of improving data accuracy and organizational efficiency.

The implementation of an easy-to-use interface, as demonstrated in the live deployment, ensures that both administrators and students can navigate hostel activities with minimal effort. Ultimately, this project provides a scalable and reliable framework that significantly reduces the administrative workload, meeting all the goals established during the initial design and testing phases.

# 📜 License
This project is licensed under the MIT License.