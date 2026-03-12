# TaskNet
# ⚡ TaskNet – Crowdsourced Local Marketplace

![TaskNet](https://img.shields.io/badge/TaskNet-Local%20Marketplace-ff6b35?style=for-the-badge)
![PHP](https://img.shields.io/badge/PHP-Backend-777bb4?style=for-the-badge&logo=php)
![JavaScript](https://img.shields.io/badge/JavaScript-Frontend-f7df1e?style=for-the-badge&logo=javascript)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql)
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-Location-7ebc6f?style=for-the-badge)

> A crowdsourced local marketplace connecting users across Sri Lanka with skilled professionals — plumbers, electricians, technicians, gardeners, and more. Find, hire, and rate service providers in your local area effortlessly.

---

## 📌 Project Overview

TaskNet bridges the gap between customers and local service professionals in Sri Lanka. The platform provides a seamless experience for users to search for skilled workers by location and category, book appointments, communicate directly, and leave ratings — all in one place.

---

## 🚀 Features

- 🔍 **Search & Filter** — Find professionals by location, service category, and ratings
- 🛠️ **Service Listings** — Professionals create detailed profiles showcasing skills and experience
- 🗺️ **Location-Based Matching** — Connect with nearby providers using GPS-based recommendations via OpenStreetMap
- 💬 **In-App Messaging** — Communicate directly with service providers
- ⭐ **Ratings & Reviews** — Rate and review professionals based on service quality
- 💳 **Secure Payments** — Online payment support for service bookings
- 🔐 **User Authentication** — Secure session-based login for customers and professionals
- 📅 **Booking System** — Schedule and manage service appointments

---

## 🛠️ Technologies Used

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | PHP |
| Database | MySQL |
| Authentication | Session-based authentication |
| Mapping & Location | OpenStreetMap |

---

## 📁 Project Structure

```
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
```

---

## ⚙️ Getting Started

### Prerequisites

- [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/) — for running PHP and MySQL locally
- A modern web browser

---

### Installation

**1️⃣ Clone the repository**
```bash
git clone https://github.com/theezz7777/tasknet.git
cd tasknet
```

**2️⃣ Start your local server**
- Open **XAMPP Control Panel**
- Start **Apache** and **MySQL**

**3️⃣ Set up the database**
- Open **phpMyAdmin** → `http://localhost/phpmyadmin`
- Create a new database named `tasknet`
- Click **Import** and select `database/tasknet.sql`

**4️⃣ Configure database connection**

Open `config.php` and update with your details:
```php
<?php
define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'tasknet');
?>
```

**5️⃣ Run the app**
- Place the project folder inside `htdocs` (XAMPP) or `www` (WAMP)
- Open your browser and go to:
```
http://localhost/tasknet
```

---

## 🎮 Example Usage

1. **Register / Login** — Customers and professionals sign up with their details
2. **Search for Services** — Enter a location and service category to find professionals
3. **View Profiles** — Check ratings, experience, and availability of providers
4. **Book a Service** — Schedule an appointment and chat with the provider
5. **Complete & Rate** — After service, rate and review the professional

---

## 🌐 Key Pages

| Page | Description |
|---|---|
| `index.html` | Landing page |
| `login.php` | User authentication |
| `profile.php` | User and professional profiles |
| `search.php` | Search and filter professionals |
| `services.php` | Browse service categories |
| `booking.php` | Schedule appointments |
| `contact.php` | Contact and support |

---

## 📄 License

This project is developed for academic purposes.

© 2026 TaskNet. All rights reserved.
