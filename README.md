# Debug Battle 05 – Ecommerce Admin Dashboard

## Challenge Information

**Due Date:** June 4, 2026, 12:00 PM IST
**Batch:** Kodex Batch
**Total Points:** 100

### Buggy Repository

Download the project ZIP file from the following link:

https://drive.google.com/file/d/1iXwZhjJ4IBt4UnR4YHFob16u6X3psmPz/view?usp=sharing



> **Note:** Download the ZIP file using the provided Google Drive link.

---

## Challenge Overview

Welcome to the Debug Battle!

You've been handed a modern Ecommerce Admin Dashboard built using React, Vite, Node.js, Express.js, MongoDB, and JWT Authentication. The platform is designed to help administrators manage products, inventory, orders, customers, and store operations from a centralized dashboard.

Everything appears to be production-ready — but there's a catch.

The codebase has been intentionally injected with multiple bugs across both the frontend and backend. Some issues are easy to spot, while others are hidden deep within application logic, API integrations, authentication flows, state management, database operations, and project configuration.

Your mission is to identify and fix every issue while preserving the existing architecture and functionality.

---

## Rules

1. Find and fix all bugs in the codebase.
2. Bugs are spread across multiple files — no file is safe.
3. Do not change the overall architecture or project structure.
4. Fix only what is broken.
5. The application should be fully functional after all bugs are fixed.
6. Verify both frontend and backend functionality before submission.

---

## Buggy Version Behaviors

The application is intentionally broken in several places. Participants may observe behaviors such as:

* Login and authentication issues.
* Dashboard data failing to load correctly.
* Product creation and management workflows behaving unexpectedly.
* Inventory values not reflecting actual stock levels.
* Orders being accepted or rejected under incorrect conditions.
* Missing notifications and UI feedback.
* Incorrect dashboard calculations and statistics.
* Infinite loading screens in certain scenarios.
* Data being saved in incorrect formats.
* Backend errors with insufficient debugging information.

---

## Application Features

The Ecommerce Admin Dashboard allows administrators to:

* Authenticate and access protected routes.
* Create, edit, and manage products.
* Manage product variants and inventory.
* Upload product images.
* View and manage customer orders.
* Track stock levels across products.
* Monitor dashboard statistics.
* Manage authentication sessions.
* Receive visual feedback through notifications and alerts.

Your goal is to restore all features to their intended functionality.

---

## Project Structure

```text
frontend/
└── src/
    ├── components/
    ├── context/
    ├── pages/
    ├── services/
    └── App.jsx

backend/
├── controllers/
├── middleware/
├── models/
├── routes/
├── config/
└── server.js
```

## Tech Stack

### Frontend

* React
* Vite
* Context API
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Multer

---

## Getting Started

### Install Frontend Dependencies

```bash
npm install
```

### Install Backend Dependencies

```bash
cd server
npm install
```

### Start Backend

```bash
npm run dev
```

### Start Frontend

```bash
npm run dev
```

---

## Objective

Read the code carefully, trace the application flow, inspect API requests, verify business logic, and identify every bug hidden throughout the project.

The goal is to restore the Ecommerce Admin Dashboard to a fully functional state while maintaining the existing architecture and design patterns.

Good luck, and may the best debugger win!
