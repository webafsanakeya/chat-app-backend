[![Render](https://img.shields.io/badge/Backend-Render-red)](https://chat-app-backend-iocn.onrender.com)
[![Node.js](https://img.shields.io/badge/Node.js-22.16.0-green)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.x-orange)](https://expressjs.com/)

A **Real-Time Chat Application Backend** built with **Node.js, Express, and Socket.IO**.  
Supports authentication, messaging, and real-time online user tracking.

---

## 🌟 Features

- User Authentication (Signup / Login) with JWT
- Real-time messaging via **Socket.IO**
- Online users tracking
- Profile update
- REST API for frontend integration
- MongoDB Atlas database integration

---

## 💻 Tech Stack

- Node.js + Express  
- Socket.IO  
- MongoDB Atlas  
- Cloudinary (for media uploads)  
- JWT authentication  
- CORS  

---

## 🔗 Live Demo

Backend live: [Chat App Backend](https://chat-app-backend-iocn.onrender.com/api/status)

---

## 🔧 Setup Instructions

1. Clone the repo:

```bash
git clone https://github.com/webafsanakeya/chat-app-backend.git
cd chat-app-backend
Install dependencies:

bash
Copy code
npm install
Create .env file:

env
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_cloud_api_key
CLOUDINARY_API_SECRET=your_cloud_api_secret
Start server:

bash
Copy code
npm run start
# or if using nodemon
npm run dev
Server will run at http://localhost:5000
