# ChitChat — MERN Real-Time Chat Application

A full-stack chat application with authentication, one-to-one and group chats, user search, profile picture upload, and real-time messaging using Socket.IO. Built with MongoDB, Express, React, Node.js, and Chakra UI.

---

## Features
- User authentication and authorization with JWT  
- Password encryption using bcrypt  
- User search with regex (name/email)  
- One-to-one and group chat creation and management  
- Real-time messaging with Socket.IO (typing indicators, notifications)  
- Profile picture uploads with Cloudinary  
- Responsive UI built with Chakra UI  
- API tested with Postman  

---

## Tech Stack
**Frontend:** React, React Router v5, Axios, Chakra UI, React-Scrollable-Feed, React-Notification-Badge, React-Lottie  
**Backend:** Node.js, Express.js, Mongoose, dotenv, express-async-handler, bcryptjs, JSON Web Token  
**Realtime:** Socket.IO, socket.io-client  
**Database & Infra:** MongoDB Atlas, Cloudinary, Nodemon, Concurrently (optional for dev)  

## Project Structure
chitchat/
├─ backend/
│ ├─ server.js
│ ├─ config/ (db.js, generateToken.js)
│ ├─ controllers/ (userControllers.js, chatControllers.js)
│ ├─ models/ (userModel.js, chatModel.js)
│ ├─ routes/ (userRoutes.js, chatRoutes.js)
│ └─ data/data.js
└─ frontend/
├─ src/
│ ├─ pages/ (HomePage.js, ChatPage.js)
│ ├─ components/ (Auth/, Chat/, common/)
│ ├─ App.js
│ └─ index.js
└─ package.json

---

## Setup and Run Instructions
1. Clone repo:  
   ```bash
   git clone https://github.com/Tahniat-Niger/Chat_App.git
   cd Chat_App
## Backend setup:
cd backend,
npm install,
npm run dev


## Frontend setup:
cd frontend,
npm install,
npm start

