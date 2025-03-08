# User Management System

A modern and professional CRUD application built with Node.js, Express.js, PostgreSQL, and Sequelize.

## Features

- Create, read, update, and delete users
- Modern and responsive UI
- Form validation
- Animated notifications
- Loading states and smooth transitions
- Mobile-friendly design

## Prerequisites

- Node.js (v14 or higher)
- PostgreSQL database

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd Personal_Finance_App_Development
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Create a PostgreSQL database named `finance_db`

4. Configure environment variables:
   - Rename `.env.example` to `.env` (or create a new `.env` file)
   - Update the database credentials in the `.env` file

## Running the Application

1. Start the server:
   ```
   npm start
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## API Endpoints

- `GET /api/users` - Get all users
- `GET /api/users/:id` - Get a specific user
- `POST /api/users` - Create a new user
- `PUT /api/users/:id` - Update a user
- `DELETE /api/users/:id` - Delete a user

## Technologies Used

- **Backend**:
  - Node.js
  - Express.js
  - Sequelize ORM
  - PostgreSQL

- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript (ES6+)
  - Font Awesome icons

## Project Structure

```
├── config/             # Configuration files
│   └── database.js     # Database configuration
├── models/             # Sequelize models
│   └── User.js         # User model
├── public/             # Frontend files
│   ├── index.html      # Main HTML file
│   ├── styles.css      # CSS styles
│   └── script.js       # Frontend JavaScript
├── routes/             # API routes
│   └── userRoutes.js   # User routes
├── .env                # Environment variables
├── server.js           # Main server file
└── README.md           # Project documentation
```

## License

This project is licensed under the ISC License.