# Vanilla E-Commerce Course

> Build a production-style e-commerce website with **HTML**, **CSS**, and **Vanilla JavaScript** in **12 weeks** by developing a complete, end-to-end application for a online Coffee Shop .

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)
![Project](https://img.shields.io/badge/Project-E--Commerce-success)

---

## 📖 Overview

This repository contains a **12-week, project-based curriculum** designed to teach modern front-end web development through a single real-world project.

Instead of learning HTML, CSS, and JavaScript in isolation, you'll build a complete e-commerce platform from scratch, implementing features incrementally each week.

By the end of the course, you'll have a responsive, production-style application that demonstrates practical front-end engineering skills and serves as a strong portfolio project.

---

# 🎯 Learning Outcomes

After completing this course, you will be able to:

- Build semantic HTML5 websites
- Create responsive layouts using Flexbox and CSS Grid
- Write clean, modular JavaScript (ES6+)
- Manipulate the DOM
- Consume REST APIs using Fetch API
- Build reusable UI components
- Manage application state
- Handle authentication
- Implement shopping cart functionality
- Build checkout workflows
- Organize medium-sized front-end projects
- Deploy applications to production

---

# 🛒 Final Project

The final application includes:

- Responsive Landing Page
- Product Catalog
- Product Details
- Shopping Cart
- User Authentication
- Checkout Flow
- Order History
- User Dashboard
- Admin Dashboard
- Notification System

---

# 🏗 Architecture

```text
                   Frontend
                         │
                         ▼
                HTML + CSS + JS
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
     Fetch API      LocalStorage      JSON
                         │
                         ▼
                  Mock REST APIs
                         │
 ┌───────────────────────────────────────────────┐
 │                                               │
 │  Authentication Service                       │
 │  Product Service                              │
 │  Cart Service                                 │
 │  Order Service                                │
 │  Notification Service                         │
 │                                               │
 └───────────────────────────────────────────────┘
```

---

# 📦 Microservices

## 1. Authentication Service

Responsible for:

- User registration
- Login
- Logout
- Profile management
- Session management

Endpoints

```
POST /register
POST /login
POST /logout
GET  /profile
PATCH /profile
```

---

## 2. Product Service

Responsible for:

- Product catalog
- Categories
- Search
- Product details
- Inventory

Endpoints

```
GET /products
GET /products/{id}
GET /categories
POST /products
PUT /products/{id}
DELETE /products/{id}
```

---

## 3. Cart Service

Responsible for:

- Shopping cart
- Cart summary
- Quantity management
- Totals
- Discounts

Endpoints

```
GET /cart
POST /cart/items
PATCH /cart/items/{id}
DELETE /cart/items/{id}
DELETE /cart
```

---

## 4. Order Service

Responsible for:

- Checkout
- Orders
- Payment status (mock)
- Order history
- Invoice

Endpoints

```
POST /checkout
POST /orders
GET /orders
GET /orders/{id}
PATCH /orders/{id}/cancel
```

---

## 5. Notification Service

Responsible for:

- Toast notifications
- Email notifications (mock)
- In-app notifications

Endpoints

```
POST /notifications
GET /notifications
PATCH /notifications/{id}/read
DELETE /notifications/{id}
```

---

# 🗓 Course Roadmap

| Week | Outcome |
|-------|---------|
| 1 | Landing Page |
| 2 | Responsive Layout |
| 3 | Interactive UI |
| 4 | Product Catalog |
| 5 | Product Details |
| 6 | Shopping Cart |
| 7 | Authentication |
| 8 | Checkout |
| 9 | Order Management |
| 10 | Admin Dashboard |
| 11 | Notifications |
| 12 | Deployment & Polish |

---

# 📚 Technology Stack

## Frontend

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)

## APIs

- Fetch API
- REST API
- JSON

## Storage

- LocalStorage

## Development

- Git
- GitHub
- JSON Server (Mock API)

---

# 📂 Repository Structure

```
vanilla-ecommerce-course/

├── docs/
│
├── week-01/
├── week-02/
├── week-03/
├── week-04/
├── week-05/
├── week-06/
├── week-07/
├── week-08/
├── week-09/
├── week-10/
├── week-11/
├── week-12/
│
├── services/
│   ├── authentication-service/
│   ├── product-service/
│   ├── cart-service/
│   ├── order-service/
│   └── notification-service/
│
├── assets/
│
├── solutions/
│
├── exercises/
│
└── README.md
```

---

# 🎓 Prerequisites

No prior web development experience is required.

You only need:

- A computer
- A modern web browser
- VS Code
- Git
- Willingness to learn

---

# ⏱ Weekly Commitment

Approximately **3 hours per week**.

Typical breakdown:

| Activity | Time |
|----------|------|
| Learn new concepts | 45 min |
| Build project features | 90 min |
| Debug & Refactor | 30 min |
| Git & Review | 15 min |

---

# 🏆 What You'll Build

By the end of the course, you'll have a portfolio-ready project featuring:

- Responsive Design
- Product Catalog
- Search & Filtering
- Shopping Cart
- Authentication
- Checkout
- Order History
- Admin Dashboard
- Notification System
- Clean Project Structure

---

# 🚀 Future Improvements

After completing this course, you can continue with:

- React
- Next.js
- TypeScript
- Node.js
- Express
- PostgreSQL
- Docker
- Authentication with JWT
- Payment Integration (Stripe)
- Cloud Deployment

---

# 🤝 Contributing

Contributions are welcome.

If you'd like to improve the course material, fix issues, or add exercises, feel free to open an issue or submit a pull request.

---

# 📄 License

This project is licensed under the MIT License.

---

## ⭐ If you find this repository helpful, consider giving it a star!
