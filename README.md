# 🧪 Online Test Platform

An advanced **MERN-based Online Test Platform** that enables administrators to create and schedule coding and MCQ-based assessments while allowing students to participate in live tests with automatic evaluation. The platform integrates **Judge0 API** for secure code execution, **Cloudinary** for file management, and **JWT Authentication** for role-based access control.

---

## 🌐 Live Demo

🔗 **Application:** https://onilnetest.netlify.app/

---

## ✨ Features

### 👨‍🏫 Admin Panel
- Create, edit, and delete online tests
- Schedule tests with configurable start and end times
- Add both **MCQ** and **Coding** questions
- Upload coding input/output test files using **Cloudinary**
- Monitor student submissions
- View real-time leaderboard and test analytics

### 👨‍🎓 Student Panel
- Register using a unique test code
- View upcoming and active tests
- Attempt MCQ and coding questions
- Instant auto-evaluation after submission
- View scores and rankings

### ⚙️ Technical Highlights
- JWT-based authentication with **Admin** and **Student** roles
- Secure password hashing using **bcrypt**
- Live code execution using **Judge0 API**
- MongoDB schema design for tests, questions, and submissions
- Cloudinary integration for managing coding test files
- Protected routes with role-based authorization
- RESTful API architecture using Express.js

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|------------|
| **Frontend** | React.js, Vite, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JWT, bcrypt |
| **Code Execution** | Judge0 API |
| **File Storage** | Cloudinary |

---

## 🚀 Installation

### Clone Repository

```bash
git clone <repository-url>
cd Online-Test-Platform
```

---

## Backend Setup

```bash
cd backend
npm install
npm run dev
```

Create a `.env` file inside the backend folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
JUDGE0_API_KEY=your_judge0_api_key
```

---

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 📂 Project Structure

```
Online-Test-Platform/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── context/
│   │   └── App.jsx
│   ├── public/
│   └── package.json
│
└── README.md
```

---

## 🔒 Authentication

- JWT-based Authentication
- Role-Based Access Control (Admin & Student)
- Protected Routes
- Secure Password Hashing using bcrypt

---

## 🎯 Core Functionalities

- Live Coding Tests
- MCQ Tests
- Automatic Code Evaluation
- Test Scheduling
- Submission Tracking
- Leaderboard Generation
- Cloudinary File Uploads
- RESTful APIs

---

## 📌 Future Improvements

- AI-powered performance analysis
- Test analytics dashboard
- Email notifications
- Code plagiarism detection
- Fullscreen & tab-switch monitoring
- Timer synchronization using WebSockets
- Docker deployment
- CI/CD pipeline

---

## 📄 License

This project is licensed under the MIT License.
