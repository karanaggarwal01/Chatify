# 💬 Chatify — Realtime Chat Application

**Chatify** is a full-stack **real-time chat application** built using the **MERN stack** and **Socket.io**, designed with a production-oriented architecture focusing on security, scalability, and real-time communication.

---

## 🚀 Key Features

- Secure user authentication using **JWT** and **HTTP-only cookies**
- Real-time one-to-one messaging with **Socket.io**
- Persistent message storage with **MongoDB**
- Media uploads and profile images via **Cloudinary**
- Transactional email support using **Resend**
- API protection and rate limiting with **Arcjet**
- Modern, responsive UI built with **React, Tailwind CSS, and DaisyUI**

---

## 🛠 Tech Stack

**Frontend**
- React, Vite
- Zustand (state management)
- Tailwind CSS, DaisyUI
- Socket.io Client

**Backend**
- Node.js, Express.js
- MongoDB, Mongoose
- Socket.io
- JWT, bcrypt

**Third-Party Services**
- Cloudinary (media storage)
- Resend (emails)
- Arcjet (API security)

---

## 📁 Project Structure (High-Level)

```
Chatify/
├── backend/    # REST APIs, Socket.io server, auth & business logic
└── frontend/   # React application and UI
```

---

## ⚙️ Environment Setup

Create a `.env` file inside the `backend` directory:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_API_KEY=your_cloudinary_key
RESEND_API_KEY=your_resend_key
ARCJET_KEY=your_arcjet_key
```

---

## ▶️ Running Locally

```bash
# Backend
cd backend
npm install
npm run dev

# Frontend
cd frontend
npm install
npm run dev
```

---

## 🔌 Real-Time Architecture

- Socket.io is used for **persistent, bidirectional communication**
- Each chat operates within a dedicated socket room
- Authentication middleware secures socket connections
- REST APIs handle auth and data fetching, while sockets manage live messaging

This separation ensures **scalability and maintainability**.

---


## 📌 Why This Project Matters

Chatify demonstrates:
- Real-world **full-stack system design**
- Secure authentication and session handling
- Practical use of **WebSockets** in production
- Integration of modern third-party services
- Clean separation of frontend, backend, and real-time layers

---


## 👨‍💻 Author

Made with ❤️ by **Karan Aggarwal**  
Connect with me - [LinkedIn](https://www.linkedin.com/in/karanagg2005)
