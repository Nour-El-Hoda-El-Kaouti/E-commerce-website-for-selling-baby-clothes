# 🍼 BabyBoutique - E-Commerce Platform for Baby Clothes

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![PHP](https://img.shields.io/badge/Backend-PHP_7/8-777BB4?logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?logo=mysql&logoColor=white)

## 📖 About the Project
**BabyBoutique** is a fully functional, full-stack e-commerce web application dedicated to retailing baby clothing and accessories. The platform was designed to provide a seamless, intuitive, and secure shopping experience for parents, while offering a robust backend for administrators to manage the store's catalog, orders, and customer data.

The project focuses on clean code architecture, responsive web design, and efficient relational database management to handle real-world e-commerce operations.

---

## ✨ Key Features

### 🛒 Customer-Facing (Frontend)
* **User Authentication:** Secure registration, login, and profile management.
* **Product Catalog:** Browse baby clothes by categories (e.g., newborn, toddler, accessories), sizes, and colors.
* **Advanced Search & Filtering:** Easily find products using keywords, price ranges, and specific attributes.
* **Shopping Cart:** Add, remove, and update item quantities with real-time price calculations. 

### ⚙️ Administration Panel (Backend)
* **Dashboard:** Overview of key metrics (total sales, recent orders, registered users).
* **Product Management (CRUD):** Add, edit, delete, and categorize products, including image uploads and stock management.
* **Order Processing:** View, update order statuses (Pending, Shipped, Delivered), and manage customer requests.
* **User Management:** View customer profiles and manage user accounts.
* **Category Management:** Create and organize product categories and sub-categories.

---

## 🛠️ Tech Stack

| Role | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla), Responsive UI |
| **Backend** | PHP (Object-Oriented / Procedural) |
| **Database** | MySQL (Relational Database Management) |
| **Server** | Apache (via XAMPP / WAMP / LAMP) |
| **Tools** | Git, GitHub, phpMyAdmin |

---

## 🗄️ Database Architecture
The application is powered by a normalized **MySQL** database designed to ensure data integrity and fast querying. Key entities include:
* `Users` (Customers & Admins)
* `Products` & `Categories`
* `Orders` & `Order_Items` (Linking orders to specific products and quantities)
* `Reviews` (Optional: Customer feedback on products)

---

## 🚀 Getting Started (Installation)

Follow these steps to set up the project locally on your machine.

### Prerequisites
* A local server environment like **XAMPP**, **WAMP**, or **MAMP**.
* PHP 7.4 or higher.
* MySQL 5.7 or higher.

### Installation Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Nour-El-Hoda-El-Kaouti/E-commerce-website-for-selling-baby-clothes.git
