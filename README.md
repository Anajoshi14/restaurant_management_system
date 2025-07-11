# 🍽️ Restaurant Management System

A backend service built in **Golang** for managing restaurant operations like orders, menu items, categories, tables, and more. Built using the Gin web framework and PostgreSQL.

---

## 🚀 Features

- 🍛 Add, update, and view menu items and categories  
- 🧾 Place and manage orders  
- 🪑 Assign and manage restaurant tables  
- 👩‍🍳 Manage food items across categories  
- 📦 Clean folder structure with modular design

---

## 🛠️ Tech Stack

| Layer         | Technology     |
|---------------|----------------|
| Language      | Golang         |
| Web Framework | Gin            |
| ORM           | GORM           |
| Database      | PostgreSQL     |
| Config        | `.env` file    |

---

## 📁 Project Structure

```bash
restaurant_management_system/
├── controllers/         # Request handlers
├── models/              # GORM models
├── routes/              # API routing
├── database/            # DB config and connection
├── middleware/          # Authorization / custom middlewares
├── helpers/             # Utility functions
├── go.mod / go.sum      # Go modules
├── main.go              # Entry point
└── README.md            # Documentation
