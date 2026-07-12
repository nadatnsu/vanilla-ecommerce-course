# 🗺️ Vanilla E-Commerce Course Roadmap

> A 12-week, project-based roadmap for learning **HTML**, **CSS**, and **Vanilla JavaScript** by building a production-style e-commerce website.

---

# Course Timeline

| Week | Module | Outcome |
|------|---------|---------|
| 1 | HTML Foundations | Build the landing page |
| 2 | CSS Foundations | Make the website responsive |
| 3 | JavaScript Foundations | Add interactive UI |
| 4 | Product Service | Build the product catalog |
| 5 | Product Service | Build product details |
| 6 | Cart Service | Build a shopping cart |
| 7 | Authentication Service | Build authentication |
| 8 | Order Service | Build checkout |
| 9 | Order Service | Build order management |
| 10 | Notification Service | Build notifications |
| 11 | Observability Service | Add monitoring & logging |
| 12 | Integration & Deployment | Production-ready application |

---

# Visual Roadmap

```text
HTML
│
├── Week 1
│
CSS
│
├── Week 2
│
JavaScript
│
├── Week 3
│
├──────────────────────────────────────────────
│
Product Service
│
├── Week 4
├── Week 5
│
├──────────────────────────────────────────────
│
Cart Service
│
├── Week 6
│
├──────────────────────────────────────────────
│
Authentication Service
│
├── Week 7
│
├──────────────────────────────────────────────
│
Order Service
│
├── Week 8
├── Week 9
│
├──────────────────────────────────────────────
│
Notification Service
│
├── Week 10
│
├──────────────────────────────────────────────
│
Observability Service
│
├── Week 11
│
├──────────────────────────────────────────────
│
Integration & Deployment
│
└── Week 12
```

---

# Weekly Breakdown

## Week 1 — HTML Foundations

### Goal

Build a semantic landing page.

### Topics

- HTML5
- Semantic Elements
- Typography
- Images
- Links
- Lists
- Tables
- Forms
- Accessibility Basics

### Deliverables

- Navigation
- Hero Section
- Featured Products
- Categories
- Footer

---

## Week 2 — CSS Foundations

### Goal

Create a responsive user interface.

### Topics

- Selectors
- Box Model
- Colors
- Typography
- Flexbox
- CSS Grid
- Responsive Design
- Media Queries
- Transitions
- Animations

### Deliverables

- Responsive Layout
- Mobile Navigation
- Product Grid
- Responsive Footer

---

## Week 3 — JavaScript Foundations

### Goal

Add interactivity.

### Topics

- Variables
- Data Types
- Functions
- Arrays
- Objects
- Loops
- Conditionals
- DOM Manipulation
- Events
- Local Storage
- Fetch API

### Deliverables

- Mobile Menu
- Dark Mode
- Product Search
- Image Slider
- Form Validation

---

# Product Service (Weeks 4–5)

## Goal

Build the shopping experience.

### Responsibilities

- Product Catalog
- Categories
- Product Details
- Search
- Filtering
- Sorting

### Endpoints

```http
GET    /products
GET    /products/{id}
GET    /categories
POST   /products
PUT    /products/{id}
DELETE /products/{id}
```

### Deliverables

- Product Listing
- Product Cards
- Product Details
- Search
- Category Filter
- Sort Products
- Pagination

---

# Cart Service (Week 6)

## Goal

Implement shopping cart functionality.

### Responsibilities

- Add to Cart
- Remove Item
- Update Quantity
- Calculate Totals
- Discounts
- Shipping

### Endpoints

```http
GET    /cart
POST   /cart/items
PATCH  /cart/items/{id}
DELETE /cart/items/{id}
DELETE /cart
```

### Deliverables

- Shopping Cart
- Cart Summary
- Quantity Controls
- Price Calculation

---

# Authentication Service (Week 7)

## Goal

Implement user authentication.

### Responsibilities

- Register
- Login
- Logout
- Profile
- Session Management

### Endpoints

```http
POST /register
POST /login
POST /logout
GET  /profile
PATCH /profile
```

### Deliverables

- Registration Form
- Login Form
- Profile Page
- Protected Pages

---

# Order Service (Weeks 8–9)

## Goal

Build checkout and order management.

### Responsibilities

- Checkout
- Orders
- Invoice
- Order History
- Mock Payments

### Endpoints

```http
POST /checkout
POST /orders
GET  /orders
GET  /orders/{id}
PATCH /orders/{id}/cancel
```

### Deliverables

- Checkout
- Order Confirmation
- Order History
- Invoice
- Order Details

---

# Notification Service (Week 10)

## Goal

Provide application feedback.

### Responsibilities

- Toast Messages
- Alerts
- Success Messages
- Error Messages
- Email Simulation

### Endpoints

```http
POST   /notifications
GET    /notifications
PATCH  /notifications/{id}/read
DELETE /notifications/{id}
```

### Deliverables

- Toast Component
- Notification Center
- Success Alerts
- Error Alerts

---

# Observability Service (Week 11)

## Goal

Introduce production monitoring concepts.

### Responsibilities

- Application Logs
- Error Tracking
- Metrics
- Health Checks
- Request Monitoring

### Endpoints

```http
GET  /health
GET  /health/live
GET  /health/ready

POST /logs
GET  /logs

POST /metrics
GET  /metrics

GET  /errors
GET  /requests
```

### Deliverables

- Health Dashboard
- Log Viewer
- Metrics Dashboard
- Error Viewer
- Request History

---

# Week 12 — Integration & Deployment

## Goal

Prepare the application for production.

### Topics

- Refactoring
- Performance Optimization
- Accessibility
- SEO Basics
- Testing
- Debugging
- GitHub Pages
- Netlify
- Vercel

### Deliverables

- Complete E-Commerce Website
- Responsive Design
- Clean Codebase
- Documentation
- Production Deployment

---

# Weekly Time Commitment

**3 Hours / Week**

| Activity | Duration |
|-----------|---------:|
| Learn New Concepts | 45 min |
| Build Features | 90 min |
| Debug & Refactor | 30 min |
| Commit & Review | 15 min |

---

# Final Project

By the end of this roadmap, you will have built a production-style e-commerce application featuring:

- ✅ Responsive Landing Page
- ✅ Product Catalog
- ✅ Product Details
- ✅ Shopping Cart
- ✅ User Authentication
- ✅ Checkout Flow
- ✅ Order Management
- ✅ Notification System
- ✅ Observability Dashboard
- ✅ Admin Dashboard
- ✅ Portfolio-Ready Project

---

# Tech Stack

## Frontend

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)

## Browser APIs

- Fetch API
- Local Storage
- Session Storage

## Development Tools

- VS Code
- Git
- GitHub
- JSON Server

## Deployment

- GitHub Pages
- Netlify
- Vercel

---

# Next Steps

After completing this course, you will be well-prepared to learn:

- TypeScript
- React
- Next.js
- Node.js
- Express.js
- PostgreSQL
- Docker
- REST API Development
- Authentication with JWT
- Full-Stack Web Development
