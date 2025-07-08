# 💬 Real-Time Chat App

A full-stack real-time chat application built with **Node.js**, **Express**, **MongoDB**, and **Socket.IO**. Features include user authentication, live messaging, and more.

---

## 🚀 Features

- 🔐 User Authentication (JWT-based)
- 💬 Real-Time One-to-One
- 🖼️ Media Upload (Images via Cloudinary)
- 📜 Chat History Persistence (MongoDB)
- 🌐 RESTful API with proper MVC structure

---

## 🧱 Tech Stack

**Backend:**

- Node.js  
- Express.js  
- MongoDB with Mongoose  
- Socket.IO  
- JWT for Authentication  
- Cloudinary for Media Storage  

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/chat-app-backend.git
cd chat-app-backend
```

### 2. Install Dependencies
```bash
npm install
```
### 3. Setup .env File
```bash
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

### 4.Build the App
```bash
npm run build
```

### 5. Start the App
```bash
npm start
```
