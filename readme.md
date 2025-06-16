
---

```markdown
# 📚 Online Book Selling & Delivery System

An end-to-end, database-driven web application built with **PHP**, **MySQL**, **HTML5**, **CSS3**, and **JavaScript**, designed to simulate a real-world online bookstore. Users can browse and purchase books, and administrators can manage inventory, categories, users, and customer messages.

---

## 🔍 Overview

This project is a learning-focused eCommerce simulation for selling books online, complete with:

- Dynamic book listings (category, subcategory)
- User login/registration system
- Shopping cart and delivery order system
- Admin dashboard for inventory and content management
- Contact form to receive customer queries

---

## 💡 Features

### ✅ **User Features**
- Register and log in with email/password
- Browse books by:
  - Main categories (e.g., Business, Science, Literature)
  - Subcategories (e.g., Medical Science under Science)
- View detailed book info: title, author, price, image, e-book preview
- Search for books by keywords
- Add books to cart and proceed through checkout
- Fill shipping and contact information for delivery
- Submit inquiries via the contact page

### 🔐 **Admin Features**
- Admin login with session protection
- Add/edit/delete:
  - Books
  - Categories
  - Subcategories
- View and manage:
  - All book listings
  - Contact form submissions
- Built-in UI components (`head.inc.php`, `menu.inc.php`, `footer.inc.php`) for consistent layout
- Admin dashboard styled with custom and Bootstrap CSS

---

## 🧰 Technologies Used

| Technology     | Purpose                          |
|----------------|----------------------------------|
| PHP (Core)     | Backend logic and form handling  |
| MySQL          | Database for books, users, orders |
| HTML5/CSS3     | Structure and styling            |
| Bootstrap 3    | Responsive layout and UI components |
| JavaScript     | Form interactions and validation |
| XML            | Used for carousel configuration  |

---

## 🏗️ Project Structure

```

/bookstore/
├── index.php               # Home page with book carousel
├── detail.php              # View single book
├── booklist.php            # View all books in a category
├── checkout.php            # Order page
├── contact.php             # Contact form
├── register.php            # User signup
├── process\_*.php           # Form handlers (register, login, contact, cart)
├── viewcart.php            # Cart view
├── /admin/                 # Admin panel
│   ├── index.php           # Dashboard
│   ├── addbook.php         # Book adding interface
│   ├── all\_book.php        # Inventory listing
│   ├── category.php        # Category management
│   ├── subcategory.php     # Subcategory management
│   ├── includes/           # Shared components
│   └── process\_del*.php    # Deletion scripts
├── /css/                   # Custom styles
│   └── default.css
├── /images/                # Backgrounds and graphics
├── /home\_img/              # Carousel/book thumbnails
├── book\_store.sql          # 🧩 Database schema and sample data

````

---

## 🧾 Database Setup

### 1. Create the Database

Use **phpMyAdmin** or terminal:

```sql
CREATE DATABASE book_store;
````

### 2. Import the SQL Dump

Import the provided `book_store.sql` file:

* Contains all tables: `book`, `category`, `subcat`, `user`, `shipping_details`, `contact`
* Includes sample books, categories, and test users

---

## 🖥️ Installation Guide

### 📦 Requirements

* PHP 5.6+
* MySQL 5.x
* Apache server (via XAMPP, WAMP, LAMP, or MAMP)

### 🚀 Steps to Run Locally

1. Clone or download the project

```bash
git clone https://github.com/alakhirnayan/Online_Book_Selling_with_delivery.git
```

2. Place it in your server’s root directory:

   * `htdocs/` for XAMPP
   * `www/` for WAMP

3. Import `book_store.sql` into MySQL

4. Start Apache & MySQL via your server control panel

5. Visit the site:

```
http://localhost/bookstore/
```

---

## 🧩 Customization

* 🖼 Add your own book covers to `/home_img/` and update records in the DB
* 🧑‍💼 Change contact/admin info in `aboutus.php`, `developer.php`
* 🎨 Modify styles via `default.css` or use Bootstrap theming

---

## 📸 Screenshots (Optional)

> Replace these links with actual images or embed screenshots

* ![Homepage](screenshots/home.png)
* ![Book Details](screenshots/book-details.png)
* ![Admin Panel](screenshots/admin.png)

---

## 📄 License

This project is licensed under the **MIT License** — free for personal, educational, and commercial use with attribution.

---

## 👨‍💻 Credits

Developed by: **\[AL-AKHIR NAYAN]**
Contact: Via the email (asquiren@gmail.com) or GitHub Issues

---

