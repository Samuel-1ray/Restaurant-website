🍕 Responsive Restaurant Website
A complete, modern, and fully responsive restaurant/food ordering website built from scratch using HTML5, CSS3, Vanilla JavaScript, PHP PDO, and MySQL database.
🌟 Features
Frontend Features

✅ Responsive Header with toggle menu effect using vanilla JavaScript
✅ Responsive Hero Section with touch slider functionality
✅ Responsive Category Section using CSS Grid layout
✅ Responsive About Section using CSS Flexbox
✅ Responsive Steps Section using CSS Grid
✅ Responsive Reviews Section with touch slider
✅ Responsive Menu Section using CSS Grid
✅ Responsive Orders Section using CSS Flexbox
✅ Responsive Contact Section using CSS Flexbox
✅ Responsive Search Form section
✅ Responsive Shopping Cart section using CSS Grid
✅ Responsive Checkout section
✅ Responsive Profile section
✅ Responsive Update Profile section
✅ Responsive Update Address section
✅ Responsive Login Form section
✅ Responsive Register Form section
✅ Responsive Footer section using CSS Grid

Backend Features

🔐 User authentication and registration system
📱 Profile management (view, update profile & address)
🛒 Shopping cart functionality
💳 Secure checkout process
📋 Order management system
🔍 Search functionality
📊 MySQL database integration with PDO

🛠️ Technologies Used
Frontend

HTML5 - Semantic markup and structure
CSS3 - Styling with Grid and Flexbox layouts
Vanilla JavaScript - Interactive functionality and touch sliders
Responsive Design - Mobile-first approach

Backend

PHP - Server-side scripting
PDO (PHP Data Objects) - Database abstraction layer
MySQL - Relational database management

📱 Responsive Design
The website is fully responsive and optimized for:

📱 Mobile devices (320px and up)
📟 Tablets (768px and up)
💻 Desktop computers (1024px and up)
🖥️ Large screens (1200px and up)

🚀 Getting Started
Prerequisites

Web server (Apache/Nginx)
PHP 7.4 or higher
MySQL 5.7 or higher
Modern web browser

Installation

Clone the repository
bashgit clone https://github.com/yourusername/restaurant-website.git
cd restaurant-website

Database Setup

Create a new MySQL database
Import the provided SQL file:

sqlmysql -u username -p database_name < database/restaurant_db.sql

Configuration

Update database connection settings in config/database.php:

php<?php
$host = 'localhost';
$dbname = 'your_database_name';
$username = 'your_username';
$password = 'your_password';
?>

Launch

Start your web server
Navigate to http://localhost/restaurant-website



🎨 Key Design Features
CSS Grid Implementation

Category Section: Dynamic grid layout for food categories
Menu Section: Responsive grid for menu items
Steps Section: Process steps in grid format
Shopping Cart: Grid-based cart item display
Footer: Multi-column footer layout

CSS Flexbox Implementation

About Section: Flexible content alignment
Orders Section: Order history display
Contact Section: Contact form and info layout

JavaScript Functionality

Toggle Menu: Mobile navigation menu
Touch Sliders: Hero section and reviews carousel
Form Validation: Client-side form validation
Cart Management: Add/remove items dynamically
Search Filter: Real-time menu item filtering

🔐 Security Features

SQL Injection Protection: Using PDO prepared statements
Password Hashing: Secure password storage with PHP password_hash()
Input Validation: Server-side and client-side validation
Session Management: Secure user session handling
CSRF Protection: Cross-site request forgery prevention

📊 Database Schema
Main Tables

users - User account information
categories - Food categories
menu_items - Restaurant menu items
orders - Customer orders
order_items - Individual order items
cart - Shopping cart items
reviews - Customer reviews

🌐 Browser Support

✅ Chrome (latest)
✅ Firefox (latest)
✅ Safari (latest)
✅ Edge (latest)
✅ Mobile browsers (iOS Safari, Chrome Mobile)

📱 Mobile Features

Touch-friendly interface
Swipe gestures for sliders
Optimized touch targets
Fast loading on mobile networks
Progressive enhancement



📝 License
This project is licensed under the MIT License - see the LICENSE.md file for details.

