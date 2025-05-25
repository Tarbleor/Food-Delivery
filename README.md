# 🍔 Food Delivery Database System

## 📌 Project Description

This is a MySQL-based backend system for a food delivery application. The system manages users, restaurants, menus, orders, delivery agents, and payments. It tracks order history and allows user ratings for restaurants.

## 🧱 Key Features

- Order tracking with delivery agent assignment
- Rating system and restaurant reviews
- Order history with timestamps
- Split payments across multiple users
- Fully normalized MySQL schema with foreign key constraints

## 📂 Project Files

- `server.js` – main backend logic
- `food_delivery.sql` – full MySQL schema
- `admin.html`, `admin.js`, `admin.css` – Admin interface
- `user.html`, `user-app.js`, `user-styles.css` – User interface

## 🚀 How to Run

1. Install MySQL and Node.js
2. Import the SQL schema:
   ```bash
   mysql -u root -p < food_delivery.sql
Install dependencies:
npm install
Run the server:
node server.js

| Method | Route              | Description             |
| ------ | ------------------ | ----------------------- |
| POST   | /api/auth/register | Register user           |
| POST   | /api/auth/login    | Login with JWT          |
| GET    | /api/restaurants   | List all restaurants    |
| GET    | /api/menu-items    | Get menu for restaurant |
| POST   | /api/orders        | Place an order          |
| GET    | /api/orders        | Get order history       |
| POST   | /api/reviews       | Submit a review         |


