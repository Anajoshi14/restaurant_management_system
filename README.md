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

🔧 Getting Started
1. Clone the Repository
git clone https://github.com/Anajoshi14/restaurant_management_system.git
cd restaurant_management_system

2. Configure Environment
Create a .env file:

env
Copy
Edit
DB_HOST=localhost
DB_PORT=5432
DB_USER=your_user
DB_PASSWORD=your_password
DB_NAME=restaurant_db

3. Start PostgreSQL
bash
Copy
Edit
createdb restaurant_db
4. Run the Application
bash
Copy
Edit
go run main.go
App will start on: http://localhost:8080

🌐 API Endpoints Overview
| Method | Endpoint           | Description             |
| ------ | ------------------ | ----------------------- |
| GET    | /menu              | Get all menu items      |
| GET    | /menu/\:id         | Get menu item by ID     |
| POST   | /menu              | Create new menu item    |
| PUT    | /menu/\:id         | Update menu item        |
| DELETE | /menu/\:id         | Delete menu item        |
| ...    | `/order`, `/table` | Similar CRUD operations |

🧪 Future Enhancements
🔐 JWT Authentication

📃 Swagger Documentation

🧪 Unit Testing

📦 Docker Support

📊 Analytics endpoints (revenue, top items)

📬 Contact
Anagha Joshi
📧 anaghajoshi1999@gmail.com
🔗 LinkedIn

