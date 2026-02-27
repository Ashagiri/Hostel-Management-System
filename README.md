# 🏨 Hostel Management System
An efficient digital solution for managing hostel operations, resident records, and administrative tasks. This system replaces manual paperwork with an automated workflow for room assignments and student management.

## 👥 Team Members

* **[Asha Giri](https://github.com/Ashagiri)** - Full Stack Developer / UI Design
* **[Komal Basnet](https://github.com/username)** - Backend & Database Management
* **[Gagan Prasai](https://github.com/username)** - Frontend Implementation
* **[Jitendra Narayan Raut](https://github.com/username)** - Documentation & Testing

# 🎯 Objectives:

To automate hostel management tasks.

To manage student, room, warden, and payment records efficiently.

To provide a secure admin login system.

To store and retrieve data using a database.

To improve accuracy and reduce paperwork.

# 🌟 Features

Student Management: Effortlessly add, update, and track student details and residency status.

Room Allocation: Manage room availability and automate the assignment process.

Fee Tracking: Keep record of payments and pending dues for each resident.

Admin Dashboard: High-level overview of total occupants, available rooms, and alerts.

Search & Filter: Quick search functionality to find students by name, ID, or room number.

# 🛠️ Built With

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Server: Apache (XAMPP / WAMP)

# ⚙️ How to Run

Follow these steps to set up and run the project locally using XAMPP or WAMP:

## 1. Prerequisites
* Install XAMPP or WAMP.

* A web browser (Chrome, Firefox, etc.).

## 2. Project Setup
1. Download/Clone the Repository: * Clone this repo or download the ZIP file.

* Move the project folder into your server's local directory:

* * XAMPP: C:/xampp/htdocs/Hostel-Management-System

* * WAMP: C:/wamp64/www/Hostel-Management-System

## 3. Database Configuration
1. Start Apache and MySQL from your XAMPP/WAMP Control Panel.
2. Open your browser and go to http://localhost/phpmyadmin/.
3. Create a new database named hostel_db (or the name specified in your config file).
4. Import the SQL file: Look for a .sql file in the project folder, click the Import tab in phpMyAdmin, and upload it to populate the tables.

## 4. Configure Connection
1. Open the database connection file (usually config.php or db_connect.php) in your code editor.

2. Ensure the credentials match your local setup:

PHP
$servername = "localhost";
$username = "root";
$password = ""; // Default is empty for XAMPP
$dbname = "hostel_db";


## 5. Launch the Application
* In your browser, navigate to: http://localhost/Hostel-Management-System/index.php

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


