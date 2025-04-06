# 👤 User Management System

A modern and professional **CRUD application** built using **Node.js**, **Express.js**, **PostgreSQL**, and **Sequelize ORM**. This project offers a clean UI, robust API, and smooth user interactions for managing user data effectively.

---

## ✨ Features

- Create, Read, Update, and Delete (CRUD) operations
- Responsive, modern UI with smooth transitions
- Form input validation and error handling
- Animated notifications and loading states
- Mobile-first design

---

## ⚡ Prerequisites

- Node.js (v14 or higher)
- PostgreSQL (v12 or higher)

---

## 🚀 Installation

1. **Clone the repository:**
```bash
git clone <repository-url>
cd Personal_Finance_App_Development
```

2. **Install dependencies:**
```bash
npm install
```

3. **Create a PostgreSQL database:**
- Database name: `finance_db`

4. **Configure environment variables:**
- Rename `.env.example` to `.env`
- Add and update the following values:
```env
DB_NAME=finance_db
DB_USER=your_postgres_username
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432
PORT=3000
```

---

## 🚧 Running the Application

1. **Start the server:**
```bash
npm start
```

2. **Access the application:**
```bash
http://localhost:3000
```

---

## 📊 API Endpoints

| Method | Endpoint           | Description          |
|--------|--------------------|----------------------|
| GET    | `/api/users`       | Get all users        |
| GET    | `/api/users/:id`   | Get a specific user  |
| POST   | `/api/users`       | Create a new user    |
| PUT    | `/api/users/:id`   | Update an existing user |
| DELETE | `/api/users/:id`   | Delete a user        |

---

## 🛠️ Technologies Used

### Backend
- **Node.js**
- **Express.js**
- **Sequelize ORM**
- **PostgreSQL**

### Frontend
- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Font Awesome** (Icons)

---

## 📂 Project Structure

```
├── config/             # Configuration files
│   └── database.js     # DB connection config
├── models/             # Sequelize models
│   └── User.js         # User schema definition
├── public/             # Static frontend files
│   ├── index.html      # Main HTML
│   ├── styles.css      # CSS styles
│   └── script.js       # Client-side logic
├── routes/             # REST API routes
│   └── userRoutes.js   # User CRUD routes
├── .env                # Environment variables
├── server.js           # Main application entry
└── README.md           # Project documentation
```

---

## 📄 License

This project is licensed under the **ISC License**.

---

> *Efficiently manage users with a polished backend and sleek frontend.*
