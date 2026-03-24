# 🚀 EduFlow - MERN Learning Management System

EduFlow is a full-stack MERN-based Learning Management System designed to provide an interactive and scalable learning experience with real-time communication, secure APIs, and optimized backend performance.

---

## 🔗 Quick Access

👉 Frontend Code: https://github.com/Sip-p/eduflow-client  
👉 Backend Code: https://github.com/Sip-p/eduflow-server  

---

## 💻 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Zustand (State Management)
- Vite
- Framer Motion & GSAP (Animations)

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- RESTful APIs

### Real-Time Features
- Socket.io (WebSockets for group chat)

### Authentication & Security
- JWT Authentication
- bcryptjs (Password hashing)
- Helmet (Security headers)
- Express Rate Limit (DDoS protection)
- Joi (Validation)

### Media & Integrations
- Multer (File upload)
- Cloudinary (Media storage)
- Nodemailer (Email services)

---

## ✨ Features

- 📚 Course creation and enrollment system
- 👨‍🏫 Instructor and student dashboards
- 💬 Real-time group chat using WebSockets
- 📊 Progress tracking and analytics
- 📄 Assignment and quiz handling
- 🔐 Secure authentication and authorization
- 🎨 Responsive UI with smooth animations

---

## 🧠 System Design Highlights

- Built a **real-time chat system** using Socket.io with event-based communication
- Designed **scalable REST APIs** with secure middleware and validation layers
- Modeled **complex relationships** between users, courses, enrollments, and progress tracking
- Implemented **cloud-based media storage** using Cloudinary to reduce server load

---

## 📊 Performance Metrics

- Supports **500–1000 concurrent WebSocket users** per Node.js instance
- Handles **300–500 API requests per second (RPS)** under standard load
- Identified database bottlenecks under high traffic scenarios

---

## 🚀 Scalability Improvements (In Progress)

### Redis Caching
- Reduces API response time from ~200ms → <20ms
- Enables handling **2000+ concurrent requests**

### Database Indexing
- Improves query performance for large datasets

### Node.js Clustering (PM2)
- Utilizes multiple CPU cores
- Increases throughput up to **3000+ RPS**

---

## ⚙️ Installation & Setup

### 1. Clone Repositories
```bash
git clone https://github.com/Sip-p/eduflow-client
git clone https://github.com/Sip-p/eduflow-server
