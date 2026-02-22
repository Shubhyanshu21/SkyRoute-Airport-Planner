# 🛣️ Route Planner Web Application

A full-stack Route Planner Web Application that calculates the shortest path between two locations using a C++ based graph algorithm engine integrated with a Node.js backend.

---

## 📌 Project Overview

This project allows users to enter a source and destination location through a web interface.  
The backend processes the request and calls a C++ program that computes the shortest path using graph algorithms (Dijkstra’s Algorithm).  
The result is then displayed dynamically using EJS templates.

---

## 🏗️ Architecture

User (Browser)
        ↓
EJS Form (Frontend)
        ↓
Express Routes
        ↓
Controller
        ↓
C++ Engine (Shortest Path Algorithm)
        ↓
Result Rendered on Webpage

---

## 💻 Tech Stack

- Node.js
- Express.js
- EJS (Embedded JavaScript Templates)
- C++
- Dijkstra’s Algorithm
- child_process (Node.js module)

---

## ⚙️ Features

- User-friendly web interface
- Shortest path calculation using graph algorithms
- Integration between JavaScript and C++
- MVC architecture
- Clean separation of concerns
- Dynamic result rendering

---

## 🧠 Algorithm Used

The C++ engine implements:

- Graph representation using adjacency list
- Dijkstra’s Algorithm for shortest path calculation

Time Complexity:
O((V + E) log V) using a priority queue.

---

## 📂 Project Structure

node-backend/
│
├── server.js
├── routes/
│   └── plannerRoutes.js
├── controllers/
│   └── plannerController.js
├── views/
│   ├── home.ejs
│   ├── index.ejs
│   └── result.ejs
├── cpp-engine/
│   └── skyroute.cpp
└── package.json

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

git clone https://github.com/YOUR_USERNAME/route-planner.git

### 2️⃣ Install Dependencies

cd node-backend  
npm install

### 3️⃣ Compile C++ Engine

g++ skyroute.cpp -o skyroute

### 4️⃣ Run Server

node server.js

Open browser:
http://localhost:PORT

---

## 🎯 Why This Project Is Unique

- Combines Node.js and C++
- Uses real graph algorithm
- Demonstrates multi-language integration
- Follows MVC architecture
- Designed for performance optimization

---

## 🔮 Future Improvements

- Add database integration
- Add map visualization (Google Maps API)
- Add user authentication
- Deploy on cloud (Render / AWS / Heroku)
- Convert C++ engine into microservice

---

## 👨‍💻 Author

Shubhyanshu Pandey

---

## 📜 License

This project is for educational purposes.
