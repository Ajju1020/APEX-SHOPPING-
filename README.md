
# 🛒 APEX SHOPPING

### 🇮🇳 Full-Stack Indian E-Commerce Platform

**APEX SHOPPING** is a modern, responsive full-stack e-commerce web application built using **PHP, MySQL, HTML, CSS, and JavaScript**. It provides an Indian-focused online shopping experience with INR pricing, GST calculation, UPI payments, order tracking, wishlist management, and an admin Seller Central dashboard.

---

## 🚀 Features

### 🛍️ Customer Shopping

* 🏠 Modern e-commerce homepage
* 🔍 Real-time product search and autocomplete
* 🏷️ Category and brand-based filtering
* ⭐ Product ratings and reviews
* 💰 INR pricing with Indian number formatting
* 🛒 Shopping cart management
* ❤️ Wishlist
* 📦 Order history
* 🏠 Delivery address management
* 🔥 Product recommendations
* 📱 Fully responsive design

### 💳 Indian Checkout

* 🇮🇳 INR currency support
* 📍 Indian address management
* 📮 6-digit PIN code validation
* 💸 UPI payment options
* 💳 RuPay / Visa / Mastercard
* 🏦 Net Banking
* 💵 Cash on Delivery
* 🧾 GST invoice generation
* 🚚 Free delivery above ₹499

The checkout supports UPI, cards, Net Banking, APEX Pay Balance, and COD.

---

## 👨‍💼 Admin / Seller Central

APEX SHOPPING includes a dedicated admin dashboard for managing the e-commerce platform.

### Admin Features

* 📊 Sales dashboard
* 📦 Order management
* 🛒 Product management
* 🗂️ Category management
* 👥 Customer management
* 📈 Sales analytics
* ⚠️ Low-stock alerts
* 🔄 Inventory restocking
* ✏️ Product CRUD operations
* 🌱 Database seeding and reset

The Seller Central portal provides KPI metrics, inventory management, order fulfillment, product/category CRUD, and catalog seeding.

---

## 🛠️ Tech Stack

| Technology   | Usage                            |
| ------------ | -------------------------------- |
| 🐘 PHP 8.0+  | Backend                          |
| 🗄️ MySQL    | Database                         |
| 🔐 PDO       | Secure database connection       |
| 🎨 HTML5     | Structure                        |
| 🎨 CSS3      | Styling & responsive UI          |
| ⚡ JavaScript | Interactive features & AJAX      |
| 🔌 REST APIs | Cart, search, wishlist & reviews |
| 🖥️ XAMPP    | Local development                |

---

## 📂 Project Structure

```text
APEX SHOPPING/
│
├── admin/
│   ├── index.php
│   ├── products.php
│   ├── orders.php
│   ├── categories.php
│   ├── users.php
│   └── seed.php
│
├── api/
│   ├── search_suggest.php
│   ├── cart_action.php
│   ├── wishlist_action.php
│   └── add_review.php
│
├── assets/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
│
├── config/
│   └── db.php
│
├── includes/
│   ├── functions.php
│   ├── header.php
│   └── footer.php
│
├── index.php
├── search.php
├── product.php
├── cart.php
├── checkout.php
├── order_success.php
├── orders.php
├── wishlist.php
├── account.php
├── addresses.php
├── login.php
├── register.php
├── logout.php
└── README.md
```

The project structure and major PHP/API modules are based on the supplied project documentation.

---

## ⚙️ Installation

### 1️⃣ Install XAMPP

Download and install **XAMPP** with:

* Apache
* MySQL
* PHP 8.0+

---

### 2️⃣ Clone the Repository

Open your terminal:

```bash
git clone https://github.com/YOUR-USERNAME/APEX-SHOPPING.git
```

Move the project into:

```text
C:\xampp\htdocs\
```

Your final path should look like:

```text
C:\xampp\htdocs\APEX-SHOPPING
```

---

### 3️⃣ Start XAMPP

Open **XAMPP Control Panel** and start:

```text
Apache  ✅
MySQL   ✅
```

---

### 4️⃣ Run the Project

Open your browser:

```text
http://localhost/APEX-SHOPPING/
```

The application is designed to initialize its database, run migrations, and seed sample Indian e-commerce products on first visit.

---

## 🔑 Demo Accounts

### 👤 Customer

```text
Email: john.sharma@example.in
Password: password123
```

Access:

* Products
* Cart
* Wishlist
* Addresses
* Orders

### 👨‍💼 Admin / Seller

```text
Email: admin@apexshopping.in
Password: admin123
```

Access:

* Seller Central
* Product Management
* Inventory
* Orders
* Categories
* Customers

The supplied project documentation lists these demo credentials and access roles.

> ⚠️ **Important:** These are demo credentials. Change/remove them before deploying the project publicly.

---

## 📱 Responsive Design

APEX SHOPPING is designed to work across:

* 💻 Desktop
* 💻 Laptop
* 📱 Android
* 📱 iPhone
* 📲 Tablet
* 🖥️ Large displays

The documented layouts cover desktop, tablet, and mobile breakpoints from approximately **320px through 4K displays**.

---

## 🌐 Access From Mobile

If your phone and computer are connected to the same Wi-Fi:

### Windows

Run:

```bash
ipconfig
```

Find your **IPv4 Address**.

Example:

```text
192.168.13.161
```

Then open on your phone:

```text
http://192.168.13.161/APEX-SHOPPING/
```

---

## 🌍 Share the Project Online

You can temporarily expose the local application using a tunneling service.

### Cloudflare Tunnel

```bash
npx cloudflared tunnel --url http://localhost:80
```

### LocalTunnel

```bash
npx localtunnel --port 80
```

### Ngrok

```bash
ngrok http 80
```

> These methods are intended for development/demo purposes. For production, deploy the application to a proper PHP/MySQL hosting environment.

---

## 🔐 Security

The project uses:

* PDO database connections
* Password hashing
* Session-based authentication
* PIN code validation
* Input validation
* Role-based admin access

For production deployment, additional security hardening should be performed, including environment-based secrets, CSRF protection, secure session cookies, rate limiting, and production payment-gateway integration.

---

## 🎯 Project Goals

The main goals of APEX SHOPPING are:

* Build a complete full-stack e-commerce application
* Understand PHP backend development
* Work with MySQL databases
* Implement CRUD operations
* Create responsive UI/UX
* Implement shopping cart functionality
* Build authentication and authorization
* Develop REST-style APIs
* Implement admin dashboards
* Practice real-world web application development

---

## 🚀 Future Improvements

Possible future upgrades:

* 🤖 AI-powered product recommendations
* 💬 AI shopping assistant
* 📍 Real-time delivery tracking
* 🔔 Push notifications
* 📧 Email order notifications
* 📱 Progressive Web App (PWA)
* 💳 Production payment gateway
* ☁️ Cloud deployment
* 🐳 Docker support
* 📊 Advanced analytics dashboard
* 🔐 Two-factor authentication

---

## 👨‍💻 Developer

### **APEX Team**

Built as a full-stack e-commerce project for **learning, portfolio, and demonstration purposes**.

---

## 📄 License

This project is intended for **educational, portfolio, and demonstration purposes**.

Product imagery and third-party assets should be used according to their respective licenses.

---

⭐ **If you found this project useful, consider giving the repository a Star!**

### 🛒 APEX SHOPPING

**Everything You Need. Before You Need It.**
