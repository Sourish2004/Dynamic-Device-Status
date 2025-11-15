# 📡 Dynamic Device Status Monitoring System  
### Real-Time IoT Dashboard with Flask, PostgreSQL, WebSockets & Chart.js

A fully dynamic, real-time, production-ready **IoT device monitoring system** built using Python Flask, PostgreSQL, Socket.IO, and a modern HTML/CSS/JS frontend.

This platform is designed to handle **100+ companies**, **thousands of devices**, **continuous sensor readings**, and **real-time online/offline detection**.

---

# ✨ Features

### 🔥 Real-Time Monitoring (Socket.IO)
- WebSocket-powered live updates  
- Devices update instantly without refreshing  
- Automatic “online/offline” detection  
- Smooth UI transitions

### 🏢 Multi-Company Architecture
- Supports **100+ companies**
- Each company contains **30+ devices**
- Fully isolated company-wise device views

### 📊 Device Detail Graphs
- Real-time Chart.js line graphs
- Auto-updating telemetry values
- Historical readings fetched from the backend

### 🎛️ Professional Dashboard UI
- Modern dark theme  
- Filters: **all**, **online**, **offline**
- Live search  
- Notification for devices coming online
- Responsive (mobile-friendly)

### 🔐 Backend Built for Scale
- Flask + Gunicorn + Eventlet (WebSockets)
- Modular routes
- Status engine to compute device availability
- Connection pooling and optimized queries

---

# 🏛️ System Architecture

