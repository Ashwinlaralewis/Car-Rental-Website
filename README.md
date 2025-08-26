🚗 Car Rental Website

A web-based car rental management system built using PHP, MySQL, JavaScript, HTML, and CSS. The platform allows customers to browse and book cars online, while the admin can manage cars, bookings, and users efficiently.

📌 Features
🔹 User Features

User registration & login

Browse available cars

Car booking system

View booking history

Secure payment integration (if configured)

🔹 Admin Features

Admin dashboard

Add, update, and delete car listings

Manage bookings and users

Approve or reject bookings

Generate reports

📂 Project Structure
Car-Rental-Website/
│── carrental/           # Core project files (PHP, CSS, JS)
│── SQL File/            # Database SQL file
│── README.md            # Documentation
│── Readme.txt
│── .gitattributes

⚙️ Installation
1. Clone the Repository
git clone https://github.com/Ashwinlaralewis/Car-Rental-Website.git
cd Car-Rental-Website

2. Setup Server Environment

You need XAMPP / WAMP / MAMP installed.

Move the carrental/ folder into your server’s root directory:

For XAMPP: htdocs/

For WAMP: www/

3. Import Database

Open phpMyAdmin in your browser

Create a new database (e.g., carrental_db)

Import the .sql file from the SQL File/ folder

4. Configure Database Connection

Open carrental/includes/config.php and update:

$servername = "localhost";
$username   = "root";
$password   = "";
$dbname     = "carrental_db";

5. Run the Project

Start Apache and MySQL in XAMPP/WAMP, then visit:

http://localhost/carrental/

👨‍💻 Credentials
Admin Login

Username: admin

Password: admin123

(Update in database if different)

📦 Requirements

PHP 7+

MySQL 5+

Apache/Nginx server

Browser (Chrome, Firefox, etc.)

🚀 Future Improvements

Add online payment gateway (Stripe/PayPal)

Advanced car search & filters

Mobile-responsive design improvements

Email/SMS notifications for bookings

👨‍💻 Author

Developed by Ashwin Lara Lewis
