# TaskNet
⚡ TaskNet – Crowdsourced Local Marketplace
📌 Project Overview
TaskNet is a crowdsourced local marketplace where users across Sri Lanka can connect with skilled professionals like plumbers, electricians, technicians, gardeners, and more. The platform enables users to find, hire, and rate service providers in their local area, making it easier to get tasks done efficiently.

🚀 Features
🔍 Search & Filter – Find professionals based on location, service category, and ratings.
🛠️ Service Listings – Professionals can create detailed profiles showcasing their skills and experience.
🗺️ Location-Based Matching – Connect with nearby service providers using GPS-based recommendations.
💬 In-App Messaging – Communicate directly with service providers.
⭐ User Ratings & Reviews – Rate and review professionals based on service quality.
💳 Secure Payments – Optional feature for online payments (if implemented).
🔐 User Authentication – Secure login for customers and service providers.
📅 Booking System – Schedule and manage service appointments.
🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL
Authentication: Session-based authentication
Mapping & Location: OpenStreetMap
📁 Project Structure
/TaskNet
│── client/             # Frontend code (HTML, CSS, JavaScript)
│── server/             # Backend code (PHP, API endpoints)
│── database/           # MySQL database scripts
│── assets/             # Static files (images, icons)
│── README.md
│── index.html          # Landing page
│── login.php           # User authentication
│── profile.php         # User and professional profiles
│── search.php          # Search functionality
│── services.php        # Service categories
│── booking.php         # Appointment scheduling
│── contact.php         # Contact and support
🚀 Getting Started
Prerequisites
Install XAMPP / WAMP (For running PHP and MySQL)
Installation
1️⃣ Clone the Repository

git clone https://github.com/mohrashard/tasknet.git
cd tasknet
2️⃣ Set Up Backend

Start XAMPP / WAMP and run Apache & MySQL
Import the database:
Open phpMyAdmin
Create a new database named tasknet
Import database/tasknet.sql
Configure database connection in config.php
🎮 Example Usage
User Registration/Login – Customers and professionals sign up.
Search for Services – Users enter a location and service category.
View Professional Profiles – Check ratings, experience, and availability.
Book a Service – Schedule an appointment and chat with the service provider.
Complete & Rate – Users rate and review the service.
