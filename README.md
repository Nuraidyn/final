# Final

## 📌 Project Overview
Final is a full-featured web application with a CRUD API built using modern technologies. The project includes user authentication, post management, a liking and commenting system, and a user profile page.

## ✨ Features
- 🔐 **Authentication** (registration, login, logout, JWT tokens)
- 👤 **User Page** with a list of user posts
- 📰 **Post Feed** — view all posts
- 🔍 **Search Posts** by keywords
- 📄 **View Post** — detailed post page
- ❤️ **Likes and Comments** for user interaction

## 🛠 Technologies Used
- 🚀 **Node.js** — JavaScript runtime environment
- ⚡ **Express.js** — web framework for building APIs
- 🗄 **MongoDB** — NoSQL database
- 📜 **Mongoose** — ORM for MongoDB
- 🔑 **JWT (JSON Web Token)** — authentication
- 🎨 **React.js** — frontend library for UI
- 🌍 **Redux** — state management
- 🎭 **Tailwind CSS** — styling

## 📥 Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/strashacc/final.git
   cd final

Install dependencies:

npm install

Configure environment variables (create a .env file and add required parameters such as MongoDB connection string and JWT secret key).

Start the server:

npm start

Start the frontend:

cd client
npm install
npm start

📡 API Endpoints

🔐 Authentication

POST /api/auth/register — Register a new user

POST /api/auth/login — Log in

POST /api/auth/logout — Log out

👤 User Management

GET /api/users/:id — Retrieve user profile

GET /api/users/:id/posts — Get user posts

PUT /api/users/profile — Update user profile

📝 Posts

GET /api/posts — Get all posts

GET /api/posts/:id — Get a specific post

POST /api/posts — Create a new post

PUT /api/posts/:id — Update a post

DELETE /api/posts/:id — Delete a post

👍 Likes and Comments

POST /api/posts/:id/like — Like/unlike a post

POST /api/posts/:id/comment — Add a comment

🔒 Authentication and Security

JWT-based authentication to secure private endpoints

Middleware protection to verify tokens

Password hashing using bcrypt

⚠️ Validation and Error Handling

Data validation using libraries like Joi or Validator.js

Proper error handling (e.g., 400 for bad requests, 401 for unauthorized access)

Global error-handling middleware

🚀 Deployment

The project is deployed on a platform such as Render, Replit, or Railway.

Environment variables store sensitive information like database connection strings and JWT secrets.

🔧 Advanced Features

Role-Based Access Control (RBAC): Users have different access levels (e.g., admin can delete posts, users can only update their own posts).

🛠 Development Mode

npm run dev



