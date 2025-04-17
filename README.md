# 🍔 HungerHaul - Food Order App [Backend]

HungerHaul is a full-stack food ordering application built with **TypeScript**. It enables users to explore menus, place orders, and track deliveries with a clean and intuitive UI. Admins can manage the platform with dedicated access, making it a complete end-to-end food ordering system.

---

## 🚀 Features

### 👤 User
- Register & login with JWT authentication
- Browse available food items
- Add items to cart
- Place orders
- View order history

### 🔐 Admin
- Role-based access control (RBAC) for secure admin functionality
- Add, update, and delete food items
- View all user orders and manage delivery status

### 🛠 Developer Experience
- Built with TypeScript for better type safety and scalability
- Automated build, test, and deployment using GitHub Actions
- API documented with Postman collection
- Modular code structure and environment-based configuration

---

## 🛠️ Tech Stack

### 🔧 Backend
- **Node.js**, **Express.js**, **TypeScript**
- **MongoDB** with **Mongoose**
- **JWT** for authentication and **RBAC**

### 🎨 Frontend
- **React.js** with **TypeScript**
- **Axios** for API communication
- **React Router** for routing

### ⚙️ DevOps & Tooling
- **GitHub Actions** for CI/CD
- **Postman** for API testing/documentation
- **dotenv** for environment variable management

---

## 🔁 Project Workflow

1. **Authentication**
   - JWT-based signup/login for users and admins
   - Role-based access to protect admin-only routes and actions

2. **Food Ordering**
   - Menu browsing, cart handling, and order placement

3. **Admin Panel**
   - Admins can manage menu items and oversee all user orders

4. **CI/CD**
   - GitHub Actions for testing, building, and deploying on push to `main`

---

## 🧪 API Documentation

All backend APIs are documented using Postman.

🔗 [Postman Collection Link](FoodOrders.postman_collection.json)

## 🔄 API Flowchart


- User Signup/Login → Receives JWT Token
- JWT Token → Used in headers for authentication
- User Role Check → Routes restricted based on role
- User: View menu, cart, order
- Admin: Manage items, view all orders
- MongoDB handles all data (users, orders, items)

---

## 💻 Getting Started Locally

### 📦 Prerequisites

- Node.js >= 18.x
- MongoDB (local instance or MongoDB Atlas)
- npm or yarn

---

### 📂 Clone the Repository

```bash
git clone https://github.com/Hrithik5/HungerHaul---Food-Order-APP.git
cd HungerHaul---Food-Order-APP
npm install
npm run dev
