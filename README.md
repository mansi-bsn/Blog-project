# Blog-project

# 🚀 Full-Stack Blog Application (Node.js + Express + MongoDB + EJS)

A fully-functional, production-ready **Blog Platform** built using  
**Node.js**, **Express.js**, **MongoDB**, **Mongoose**, **EJS templating**, and **JWT Authentication**.

This project includes **User Authentication**, **Blog CRUD operations**, **File Uploads**, **Middleware Security**, and **Responsive UI**.

---

## 🏆 Key Features

- 🔐 **Authentication System**
  - Signup / Login
  - JWT-based secure auth
  - Password hashing

- ✍️ **Blog Management**
  - Create, Read, Update, Delete (CRUD)
  - Rich content blogs
  - Image uploads via Multer

- 📁 **File Uploads**
  - Multer-based storage engine
  - Uploads stored in `/uploads`

- 🛡️ **Secure Middlewares**
  - Auth middleware
  - Route protection
  - Error handling

- 🎨 **Responsive Frontend**
  - EJS templates
  - Static assets in `/public`

- 🗄️ **Database Layer**
  - MongoDB + Mongoose models
  - Clean schema structure

---

## 📂 Folder Structure

Blog-Projects/
│── controllers/ # Authentication + Blog controllers
│── routes/ # API & Web routes
│── models/ # Mongoose schemas
│── middlewares/ # Auth & security middlewares
│── public/ # CSS, JS, images
│── views/ # EJS templates
│── uploads/ # Uploaded files
│── db/ # Mongo connection config
│── index.js # Main app entry point
│── package.json
│── .env


---

## ⚙️ Tech Stack

| Layer        | Technology Used |
|--------------|------------------|
| Backend      | Node.js, Express.js |
| Frontend     | EJS Templates |
| Database     | MongoDB, Mongoose |
| Authentication | JWT Tokens |
| File Upload  | Multer |
| Environment  | Dotenv |

---

## 🔧 Installation & Setup

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME

2️⃣ Install Dependencies

npm install

🛣️ API & Web Routes Documentation
🔐 Auth Routes
| Method | Route     | Description         |
| ------ | --------- | ------------------- |
| POST   | `/signup` | Register a new user |
| POST   | `/login`  | Authenticate user   |

📝 Blog Routes

| Method | Route        | Description             |
| ------ | ------------ | ----------------------- |
| GET    | `/blogs`     | Show all blogs          |
| GET    | `/blogs/:id` | Single blog             |
| POST   | `/blogs`     | Create blog (protected) |
| PUT    | `/blogs/:id` | Update blog             |
| DELETE | `/blogs/:id` | Delete blog             |

🗂 Database Schemas
User Model

name
email
password
timeStamp

Blog Model

title
description
image
author
createdAt

🛡 Authentication Flow

User signs up → Password hashed
Login → JWT token generated
Token stored in cookies
Protected routes require valid token
Logout clears token

Keywords
-------
nodejs blog project
express blog application
full stack blog app
jwt authentication nodejs
multer file upload blog
mongodb blog website
node js ejs blog platform
node crud blog project
