# Web Interfaces with Bootstrap — Practice 1

This repository contains the implementation of the **frontend user interfaces** for a basic e-commerce web application. The practice focuses on using **HTML, CSS, and Bootstrap 5** to build responsive, accessible, and visually appealing pages for core user interactions.

## 🎯 Objective

Design and implement the interfaces of a web app using **Bootstrap 5** and layout best practices.

## 🚀 Features Implemented

### 🏠 Home Page (`index.html`)
- Responsive **navbar** with navigation links and dropdown for account options.
- **Carousel** showcasing featured content using Bootstrap's carousel component.
- **Shopping cart icon** with badge support using FontAwesome.
- **Product grid** with Bootstrap cards; responsive layout:
  - 4 products on large screens.
  - 3 products on medium screens.
  - 2 products on small screens.
- **Pagination** component at the bottom for navigating product pages.

### 🔐 Login Modal
- Triggered via "My Account > Login" in the navbar.
- Implemented using Bootstrap's modal structure.
- Includes input validation (required fields).
- Uses **FontAwesome icons** and **input-group** classes for visual enhancements.
- Form submission closes the modal upon successful input.

### 📝 User Registration Modal
- Accessible via "My Account > Register".
- Modal includes:
  - Inputs for name, last name, email, and password.
  - Flexbox layout for names in the same row (`.row > .col-6`).
- Validations:
  - Required fields.
  - Regex for password strength and name format.
- Input pattern and length validations applied via HTML attributes.

### 🛒 Shopping Cart Page (`shopping_cart.html`)
- Separate page rendering the user's cart.
- Uses **Bootstrap 4’s media object** structure for each product.
- Displays product name, image, and control buttons.
- Navbar reused for consistency and navigation.

### 📦 Order Details Page (`orders.html`)
- Product breakdown presented via cards, tables, or collapsible elements.
- Layout designed to resemble order history views in modern marketplaces (e.g., Amazon).
- Includes return buttons and responsive content containers.

### 📱 Responsive Design
- Layout adapted for small to large screens using Bootstrap's grid system.
- Media queries and `col-sm`, `col-md`, `col-lg` used for grid flexibility.

## 🧠 What I Learned

- Deepened my understanding of **Bootstrap’s responsive design tools**.
- Practiced **modal creation and form validation** with Bootstrap.
- Learned how to structure reusable components and navigation.
- Improved layout fluidity using **Flexbox**, **grid systems**, and **snippets**.
- Spent significant time debugging responsive behaviors and modal event management.

## ⏱️ Time Invested

Estimated: ~10 hours  
Including design iterations, validation logic, and responsiveness.

## 📦 Deliverables

- Full HTML, CSS (custom where needed), and linked images hosted online.
- All paths use **relative links** and public image sources (e.g., Unsplash).
- This repository is **public and cloneable**.

## 📝 License

This project was created for educational purposes as part of the *Computer Engineering* curriculum. All rights reserved by the original authors.

---

📘 También disponible en español: [README.es.md](README.es.md)