# 🛒 E-Shop – Online Shopping Website

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Servlet](https://img.shields.io/badge/Servlets-4B8BBE?style=for-the-badge&logo=java&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📌 Overview
**E-Shop** is a full-stack **online shopping website** built using **JSP, Servlets, Java, MySQL, HTML, CSS, and JavaScript**.  
It allows customers to browse products, add items to the cart, and place orders.  
Admins can manage products, view orders, and handle stock through a secure admin dashboard.  

This project is suitable for **learning Java Web Development** and can serve as a base for real-world e-commerce applications.

---

## ✨ Features

### 👤 User Side
- 🔑 **User Authentication** – Register/Login/Logout  
- 🛍️ Browse available products with images and details  
- 🛒 Add to Cart, Update quantity, and Remove products  
- 💳 Checkout and place orders  
- 📦 Track shipped and unshipped items  
- 👤 Manage personal profile  

### 🛠️ Admin Side
- ➕ Add new products with details  
- ✏️ Update existing product details  
- ❌ Remove products from store  
- 📦 View and manage customer orders (Shipped / Unshipped)  
- 📊 Manage stock levels  

---

## 🏗️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript, JSP  
- **Backend:** Java Servlets  
- **Database:** MySQL  
- **Server:** Apache Tomcat (8.5+)  
- **Build Tool:** Maven  

---

## 📂 Project Structure
shopping-cart-master/
│── WebContent/ # JSP pages, CSS, JS, images
│── src/ # Java source files (Servlets, Services, Beans, Utilities)
│── databases/ # Database schema & ERD
│── pom.xml # Maven build file
│── README.md # Project documentation

---

## ⚙️ Installation & Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/E-shop.git
   cd E-shop
Import into Eclipse/IntelliJ

As a Maven Project

Configure Database

Create a MySQL database shopping_cart

Import SQL file:

databases/mysql_query.sql


Update DB credentials in DBUtil.java

Run on Tomcat

Deploy project on Apache Tomcat server (v8.5+ recommended)

Access the app at:
👉 http://localhost:8080/E-shop/
