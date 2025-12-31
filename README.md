Mini User Management System

(Node.js + Express + MongoDB + React + JWT)

📌 Features

User Signup (Register)

User Signin (Login)

Password hashing (bcrypt)

JWT Authentication

MongoDB database

React frontend connected via API

🏗️ Project Structure
mini-user-management-system/
│
├── server/
│   ├── index.js
│   ├── db.js
│   ├── .env
│   ├── models/
│   │   └── User.js
│   └── routes/
│       ├── auth.js
│       └── users.js
│
└── client/
    ├── src/
    │   ├── api/
    │   │   └── auth.js
    │   └── pages/
    │       ├── Signup.jsx
    │       └── Login.jsx
    └── package.json
