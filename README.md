# MERN To-Do App

> A full-stack task management application with real-time updates, user authentication, and persistent MongoDB storage.

## 🎯 Overview

MERN To-Do App is a modern, full-stack web application built with the **MERN stack** (MongoDB, Express, React, Node.js). It demonstrates core full-stack development concepts including user authentication, RESTful API design, and responsive UI development.

## ✨ Key Features

- ✅ **User Authentication** – JWT-based secure login/signup
- ✅ **CRUD Operations** – Create, read, update, and delete tasks
- ✅ **Task Management** – Mark tasks complete/incomplete, delete tasks
- ✅ **Persistent Storage** – MongoDB for reliable data persistence
- ✅ **Responsive Design** – Works seamlessly on desktop and mobile
- ✅ **Protected Routes** – JWT middleware ensures secure access
- ✅ **Clean UI** – Intuitive and user-friendly interface

## 🛠 Tech Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | React.js, Vite, CSS3 |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB Atlas |
| **Authentication** | JWT (JSON Web Tokens), bcrypt |
| **API** | RESTful API |

## 📦 Installation & Setup

### Prerequisites
- Node.js (v14+) and npm/yarn
- MongoDB Atlas account (free tier available)
- Git

### Backend Setup

```bash
cd server
npm install
```

Create a `.env` file in the server directory:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key_here
PORT=5000
```

Start the backend server:
```bash
npm start
```
Server runs on `http://localhost:5000`

### Frontend Setup

```bash
cd client
npm install
npm run dev
```
Frontend runs on `http://localhost:5173`

## 🚀 Usage

1. **Sign up** – Create a new account
2. **Log in** – Enter your credentials
3. **Add Tasks** – Create new tasks with title and description
4. **Manage Tasks** – Mark tasks complete, update, or delete
5. **Log out** – Securely log out from your account

## 📁 Project Structure

```
MERN-To-Do-App/
├── server/                 # Backend (Node.js + Express)
│   ├── models/            # MongoDB schemas
│   ├── routes/            # API endpoints
│   ├── middleware/        # JWT authentication, error handling
│   ├── .env              # Environment variables
│   └── server.js         # Express app entry point
├── client/                 # Frontend (React + Vite)
│   ├── src/
│   │   ├── components/   # React components
│   │   ├── pages/        # Page components
│   │   └── App.jsx       # Main app component
│   └── index.html
└── README.md
```

## 📚 Learning Outcomes

This project demonstrates:
- Full-stack MERN architecture
- JWT-based authentication patterns
- RESTful API design principles
- MongoDB schema design
- React state management & hooks
- Express middleware usage
- Error handling & validation
- Responsive UI/UX design

## 🔄 What I'd Improve Next

- [ ] Add task categories and filtering
- [ ] Implement task priority levels
- [ ] Add due dates and reminders
- [ ] Real-time updates with Socket.io
- [ ] Dark mode toggle
- [ ] CI/CD pipeline with GitHub Actions
- [ ] Unit and integration tests
- [ ] Task sharing and collaboration features

## 📝 API Endpoints

```
POST   /api/auth/register     – Create new user
POST   /api/auth/login        – User login
GET    /api/tasks             – Get all user tasks
POST   /api/tasks             – Create new task
GET    /api/tasks/:id         – Get task by ID
PUT    /api/tasks/:id         – Update task
DELETE /api/tasks/:id         – Delete task
```

## 🤝 Contributing

This is a personal learning project, but feel free to fork and create your own version!

## 📄 License

MIT License – free to use and modify

## 👨‍💻 Author

**Aneeq Ur Rehman Ijaz** – Full-stack Developer  
[GitHub](https://github.com/aneeq6174) | [LinkedIn](https://linkedin.com/in/aneeq6174)

---

**Last Updated:** February 2026
