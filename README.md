# 🛒 SmartCart

SmartCart is a responsive Flask and MySQL based E-Commerce Web Application designed to provide a simple and user-friendly online shopping experience.

The application includes separate Admin and User functionalities, product management, shopping cart operations, order management, Razorpay payment integration, and invoice generation.

---

## 📌 Project Overview

SmartCart allows users to browse products, add products to their cart, manage quantities, place orders, make online payments, and download invoices.

Administrators can manage products, categories, product images, and their profile through a dedicated Admin Dashboard.

The application is designed with a responsive and professional interface that works across desktop, tablet, and mobile devices.

---

## ✨ Features

### 👤 User Features

- User Registration
- OTP Verification
- User Login
- User Dashboard
- Browse Products
- Search Products
- Filter Products by Category
- View Product Details
- Add Products to Cart
- Increase/Decrease Product Quantity
- Remove Products from Cart
- Select Products for Checkout
- Add Delivery Address
- Razorpay Payment Integration
- Payment Confirmation
- My Orders
- View Order Details
- Download Order Invoice
- User Logout

---

### 👨‍💼 Admin Features

- Admin Registration
- OTP Verification
- Admin Login
- Admin Dashboard
- Add Products
- Upload Product Images
- View Product Details
- Update Products
- Delete Products
- Search Products
- Filter Products by Category
- Admin Profile Management
- Profile Image Upload
- Admin Logout

---

## 💳 Payment Integration

SmartCart uses **Razorpay** for online payment processing.

The payment flow is:

```text
Select Products
       ↓
Shopping Cart
       ↓
Delivery Address
       ↓
Razorpay Checkout
       ↓
Payment Verification
       ↓
Order Confirmation
       ↓
My Orders
       ↓
Download Invoice