# online-doctor-appointment-booking-system
PHP Doctor Appointment System

Overview

The PHP Doctor Appointment System is a web-based application that allows patients to book appointments with doctors online. The system manages doctor schedules, patient records, and appointment bookings efficiently.

Features

User Authentication: Secure login for doctors, patients, and administrators.

Appointment Booking: Patients can schedule appointments based on doctor availability.

Doctor Management: Doctors can manage their schedules and view upcoming appointments.

Patient Records: Store and manage patient details for future reference.

Admin Dashboard: An administrator can manage doctors, patients, and appointment records.

Notifications: Email or SMS notifications for confirmed and upcoming appointments.

Responsive Design: Works on desktop and mobile devices.

Installation Guide

1. Prerequisites

Ensure your server has the following installed:

PHP (>=7.2)

MySQL or MariaDB

Apache or Nginx

phpMyAdmin (optional for database management)

2. Setup Steps

Download & Extract Files

Extract the contents of the ZIP file to your web server directory (e.g., htdocs/ for XAMPP or www/ for WAMP).

Create Database

Open phpMyAdmin.

Create a new database (e.g., doctor_appointment).

Import the SQL file (database.sql) located in the project folder.

Configure Database Connection

Open config.php in the project folder.

Update the database credentials:

$host = 'localhost';
$user = 'root';
$password = '';
$database = 'doctor_appointment';

Run the Application

Start your local server (Apache & MySQL).

Open a web browser and go to: http://localhost/doctor-appointment-system/

Usage

Admin Login

Default Admin Credentials:

Username: 123

Password: 123

Admin can manage doctors, patients, and appointments.

Doctor Panel

Doctors can log in and manage their schedules and appointments.

Patient Panel

Patients can register, log in, and book appointments.

Technologies Used

Frontend: HTML, CSS, JavaScript, Bootstrap

Backend: PHP, MySQL

Database: MySQL

Web Server: Apache/Nginx

License

This project is licensed under the MIT License.

Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
