# 🌍 Wanderlust Travel Agency Web Application

Wanderlust-remake is a full-featured travel agency website that allows users to explore, rate, and manage travel destinations. Built with a robust backend and responsive frontend, it provides seamless user experience for both admins and travelers.

---

## ✨ Features

### 🔐 Authentication & Authorization
- User registration and login/logout
- Secure password hashing
- Session-based authentication with role-based access (Admin & User)

### 👤 User Features
- Register and log in to the platform
- Add new travel destinations
- Rate and review places
- Edit or delete their own entries
- View all public travel destinations

### 🧑‍💼 Admin Features
- Full CRUD operations on all places and users
- Manage user reviews and ratings
- Secure admin panel accessible only by admins

### 🧱 Backend Stack
- **Node.js** and **Express.js** for building the RESTful server
- **MongoDB** with **Mongoose** ODM for data modeling
- Session management with `express-session`
- Middleware for authentication and authorization

### 🎨 Frontend Stack
- **HTML**, **CSS**, **JavaScript**
- **EJS** for templating and rendering dynamic pages
- Responsive design for desktop and mobile devices

---

## 📁 Folder Structure

 awara-travel-app
- ├── models/ # Mongoose models (User, Place, Rating
- ├── routes/ # Route files (auth, user, admin, places)
- ├── views/ # EJS templates
- ├── public/ # Static assets (CSS, images, client-side JS)
- ├── middleware/ # Custom middleware for auth & role check
- ├── .env # Environment configuration file
- ├── app.js # Entry point for Express app
- └── package.json # NPM configuration and dependencies
