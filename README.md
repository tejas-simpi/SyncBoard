# 🧑‍🎨 SyncBoard

**SyncBoard** is a real-time collaborative whiteboard web app built with **Node.js**, **Express**, **MongoDB**, **Socket.IO**, and **EJS**. It allows multiple users to join a shared drawing board, sketch ideas together, and save their boards. Users can authenticate, create sessions (rooms), and share links for real-time collaboration.

---

## 🚀 Features

- ✅ User authentication (register/login/logout)
- ✅ Create or join shared drawing rooms
- ✅ Real-time drawing with WebSocket (Socket.IO)
- ✅ Shareable room links for collaboration
- ✅ Optional canvas saving and history (coming soon)
- ✅ Clean and responsive EJS-based frontend

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript, EJS (Embedded JavaScript)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Real-time Communication**: Socket.IO
- **Authentication**: Sessions & bcrypt
- **Templating**: EJS

---

## 🏢 Structure

SyncBoard/
├── public/             # Static files (CSS, JS)
├── views/              # EJS templates
├── routes/             # Express routes
├── models/             # Mongoose schemas
├── socket/             # Socket.IO logic
├── server.js           # Main app entry point
├── .env                # Environment variables (not committed)
├── .gitignore
└── README.md
