# Laravel 12 CRUD Application

This is a **basic Laravel 12 CRUD (Create, Read, Update, Delete) application** built for learning purposes and portfolio demonstration.  
The project focuses on product management and demonstrates core Laravel concepts with a clean and simple UI.

---

## 📌 Project Overview

This application contains **three main pages**:

1. **Products List (Index Page)**
2. **Create Product Page**
3. **Edit / Update Product Page**

The goal of this project is to practice Laravel fundamentals and showcase CRUD functionality for internship-level understanding.

---

## 🧩 Features

### 🔹 Products List (Index Page)
- Displays all products in a table format
- Shows product details:
  - ID
  - Image
  - Name
  - SKU
  - Price
  - Status (Active / Inactive)
- Includes action buttons:
  - **Create** → Add a new product
  - **Edit** → Update an existing product
  - **Delete** → Remove a product

---

### 🔹 Create Product
- A form to create a new product
- Fields include:
  - Product Name
  - SKU
  - Price
  - Status
  - Image upload
- After successful creation, the product is:
  - Stored in the database
  - Redirected back to the **index page**
  - Displayed in the products list

---

### 🔹 Edit / Update Product
- Opens when clicking the **Edit** button on the index page
- Pre-fills existing product data
- Allows updating:
  - Name
  - SKU
  - Price
  - Status
  - Image
- After update, the user is redirected back to the **index page**

---

### 🔹 Delete Product
- Deletes the selected product from the database
- Uses confirmation before deletion
- After deletion:
  - Redirects back to the same index page
  - Updated list is shown without page reload issues

---

## 🎨 UI & Styling

- **Bootstrap 5** is used for layout and styling
- Responsive table design
- Bootstrap components used:
  - Buttons
  - Cards
  - Badges
  - Grid system
- Clean and simple admin-style layout suitable for beginners

---

## 🛠️ Technologies Used

- **Laravel 12**
- **PHP 8.2**
- **Bootstrap 5**
- **MySQL**
- Blade Templates
- Laravel Routing & Controllers

---

## 🎯 Purpose of This Project

- Practice Laravel CRUD operations
- Understand MVC architecture
- Learn Blade templating
- Build a strong **portfolio project**
- Prepare for **internship opportunities**

This project is intentionally kept simple to focus on Laravel fundamentals rather than complex features.

---

## 🚀 Future Improvements (Optional)

- Search & filter products
- Pagination
- Authentication (Admin Login)
- Soft delete
- Validation messages
- AJAX-based delete

---

## 👨‍💻 Author

**Muhammad Sufyan**  
Laravel Developer (Beginner / Intern Level)  
GitHub: `https://github.com/Mughal1029/Laravel-12-CRUD`

---

## 📌 Note

This is a beginner-friendly project created for learning and portfolio purposes.