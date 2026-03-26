# 🛒 ShopSphere Backend API

Production-ready E-commerce Backend API built with Node.js, Express, MongoDB, JWT Authentication, and Cloudinary.

---

## 🚀 Features

* 🔐 Authentication & Authorization (JWT)
* 👤 User Roles (Admin, Seller, Buyer)
* 🛍️ Product Management (CRUD)
* 📦 Order Management System
* ⭐ Product Reviews & Ratings
* ☁️ Image Upload (Cloudinary)
* 🔑 Password Reset (Email-based)
* 💳 Payment Method (Cash on Delivery - COD)

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB + Mongoose
* JSON Web Token (JWT)
* Cloudinary (Image Uploads)
* Nodemailer (Email Service)

---

## 📂 API Endpoints

### 🔐 Auth Routes

* `POST /api/auth/register`
* `POST /api/auth/login`
* `GET /api/auth/me`
* `POST /api/auth/forgot-password`
* `PUT /api/auth/reset-password/:token`
* `POST /api/auth/logout`

---

### 🛍️ Product Routes

* `POST /api/products` (Seller)
* `GET /api/products`
* `PUT /api/products/:id` (Seller)
* `DELETE /api/products/:id` (Seller/Admin)
* `POST /api/products/:id/reviews` (Buyer)

---

### 📦 Order Routes

* `POST /api/orders` (Buyer)
* `GET /api/orders`
* `PUT /api/orders/:id/pay` (Admin)
* `PUT /api/orders/:id/deliver` (Admin/Seller)
* `PUT /api/orders/:id/cancel`

---

## ⚙️ Environment Variables

Create a `.env` file in the root:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

EMAIL_USER=your_email
EMAIL_PASS=your_password
```

---

## ▶️ Installation & Run

```bash
# Clone repo
git clone https://github.com/your-username/shopsphere-backend.git

# Go to folder
cd shopsphere-backend

# Install dependencies
npm install

# Run server
npm run dev
```

---

## 📸 API Demo

👉 Postman Collection included
👉 Supports testing all endpoints

---

## 💡 Future Improvements

* 💳 Stripe Payment Integration
* 📊 Admin Dashboard
* 📈 Sales Analytics
* 🔔 Notifications System

---

## 👨‍💻 Author

**Your Name**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

