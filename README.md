# 🚀 AI Mock Interview Platform

An AI-powered mock interview platform that helps users prepare for technical interviews through AI-generated questions, timed interview sessions, and detailed performance feedback.

Built with React, Node.js, Express, MongoDB, Gemini AI, JWT Authentication, and Google OAuth.

---

## 🌐 Live Demo

🔗 https://interviewmock-001.vercel.app

---

## 🔑 Demo Login

> **Guest Account**
>
> Email: `demo@example.com`
>
> Password: `123@Demo`


---

## 🎥 Demo Video

Watch a complete walkthrough of the application:

[Demo Video Link](https://www.loom.com/share/017139f926f84acab7c4d3e9c6af0287)

---

## ⚡ Quick Start

```bash
git clone https://github.com/Abdul-Kalam0/AI-Mock-Interview.git

cd AI-Mock-Interview

# Install Backend Dependencies
cd server
npm install

# Install Frontend Dependencies
cd ../client
npm install
```

Run Backend:

```bash
cd server
npm run dev
```

Run Frontend:

```bash
cd client
npm run dev
```

---

## 🛠️ Technologies

### Frontend

* React (Vite)
* Tailwind CSS
* React Router DOM
* Axios
* React Toastify

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

### Authentication

* JWT Authentication
* HTTP-only Cookies
* Google OAuth

### AI Integration

* Gemini API

### Deployment

* Vercel

---



## ✨ Features

### Authentication

* User Registration & Login
* Google OAuth Login
* JWT Authentication
* Secure HTTP-only Cookie Storage
* Protected Routes

### AI Interview Experience

* AI-Generated Technical Questions
* Difficulty-Based Interview Flow
* Dynamic Question Generation
* Personalized Interview Sessions

### Interview Management

* Start New Interview Sessions
* Real-Time Timed Interviews
* Submit Answers During Interview
* Track Interview Progress

### Feedback & Analysis

* AI-Powered Performance Evaluation
* Detailed Feedback Reports
* Strengths & Weakness Analysis
* Overall Interview Score

### User Experience

* Fully Responsive Design
* Modern SaaS-Inspired UI
* Toast Notifications
* Protected Navigation

---

## 📸 Screenshots

### Login Page

![Login](./screenshots/Login.jpg)

### Dashboard

![Dashboard](./screenshots/Dashboard.jpg)

### Interview Session

![Interview](./screenshots/Interview.jpg)

### Feedback Report

![Feedback](./screenshots/Feedback.jpg)

---

## 📡 API Reference

### Authentication

#### POST `/auth/register`

Register a new user.

**Response**

```json
{
  "user": {},
  "token": "jwt_token"
}
```

---

#### POST `/auth/login`

Login user.

**Response**

```json
{
  "user": {},
  "token": "jwt_token"
}
```

---

#### GET `/auth/me`

Get authenticated user details.

**Response**

```json
{
  "user": {}
}
```

---

### Interview

#### POST `/interview/start`

Generate and start a new interview session.

**Response**

```json
{
  "interviewId": "12345",
  "questions": []
}
```

---

#### POST `/interview/answer`

Submit answer for evaluation.

**Response**

```json
{
  "success": true
}
```

---

#### GET `/interview/summary/:interviewId`

Retrieve complete interview feedback and score.

**Response**

```json
{
  "score": 85,
  "feedback": []
}
```

---

## 📁 Folder Structure

```text
AI-Mock-Interview
│
├── client
│   ├── src
│   ├── components
│   ├── pages
│   ├── context
│   ├── services
│   └── routes
│
├── server
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   └── utils
│
└── README.md
```

---

## 🔐 Security

* JWT Authentication
* HTTP-only Cookie Storage
* Protected Backend APIs
* Google OAuth Verification
* Rate Limiting
* Secure Route Authorization

---

## 📊 Project Highlights

* Full-Stack MERN Application
* Gemini AI Integration
* AI-Powered Interview Generation
* Automated Feedback & Scoring
* Real-Time Interview Workflow
* Secure Authentication System
* Production-Ready Architecture
* Responsive SaaS UI

---

## 🚧 Future Improvements

* Voice-Based AI Interviews
* Video Interview Support
* Advanced AI Evaluation
* User Analytics Dashboard
* Multi-Language Support
* Leaderboards & Rankings

---

## 📧 Contact

**Abdul Kalam**

GitHub: https://github.com/Abdul-Kalam0


Email: abdulkalamblycomp@gmail.com

---

## ⭐ Support

If you found this project useful:

⭐ Star this repository

🍴 Fork and contribute

📢 Share it with others
