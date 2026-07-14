#  🎓 Departmental Club Management System

A **comprehensive full-stack web application** designed to streamline the management and operations of student clubs within academic departments.  
This platform replaces manual workflows with a **centralized, role-based system** featuring real-time activity tracking, analytics, and secure access control.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Feature Implementation Status](#-feature-implementation-status)
- [Problem Statement](#-problem-statement)
- [Solution](#-solution)
- [Key Features](#-key-features)
- [User Roles](#-user-roles)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Demo Access](#-demo-access)
- [Database Schema](#database-schema)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [Future Enhancements](#-future-enhancements)
- [About Me](#about-me)

--- 

## 📖 Overview

The **Departmental Club Management System** is a centralized web platform built to efficiently manage multiple student clubs within an academic department.

It provides **dedicated dashboards** for:
- Students
- Club Leads
- Faculty / HODs

The system improves transparency, communication, and administrative oversight while promoting student engagement through a modern digital solution.

---


## 📌 Feature Implementation Status

>The application is deployed as an **MVP** with core role-based workflows implemented.  

Remaining modules are under active development and will be released incrementally.

### 🎓 Student Module
**Completed**
- Browse clubs
- Join clubs
- View joined clubs (My Clubs)

**In Progress**
- Activities
- Calendar
- Notifications

---

### 🧑‍💼 Club Lead Module
**Completed**
- Dashboard
- Member management

**In Progress**
- Activity management
- Attendance tracking
- Reports

---

### 👨‍🏫 Faculty Module
**Completed**
- Dashboard
- Club management (partial)

**In Progress**
- Analytics & insights


---
## ❗ Problem Statement

Traditional club management systems rely heavily on:

- Scattered spreadsheets and paper forms  
- Manual attendance tracking  
- Poor visibility for faculty advisors  
- Inefficient communication channels  
- No centralized activity history  

These limitations lead to data inconsistency, poor engagement tracking, and increased administrative effort.

---

## ✅ Solution

This platform offers:

- Role-based dashboards with secure authentication  
- Automated membership workflows  
- Digital attendance tracking  
- Real-time analytics and reporting  
- Centralized data storage and access  

---  

## ✨ Key Features

### 🎓 For Students
- **Club Discovery** – Browse all active departmental clubs  
- **Easy Registration** – One-click join requests with live status tracking  
- **Personalized Dashboard** – View your clubs and activities only  
- **Smart Notifications** – Event updates and announcements  

### 🧑‍💼 For Club Leads
- **Membership Management** – Approve/reject members with year-wise filtering  
- **Activity Planning** – Create, edit, and manage club events  
- **Attendance Tracking** – Digital attendance with historical records  
- **Progress Reports** – Insights on participation and engagement  

### 🏫 For Faculty / HOD
- **Centralized Oversight** – View all clubs from a single dashboard  
- **Analytics Dashboard** – Monitor activity levels and participation rates  
- **Leadership Management** – Assign or change club leads  
- **System Reports** – Department-wide performance insights  

---

## 👤 User Roles

| Role | Primary Functions | Key Permissions |
|------|------------------|-----------------|
| **Student** | Join clubs, view activities, receive notifications | Read access to clubs, manage own memberships |
| **Club Lead** | Manage members, create activities, track attendance | Full control over assigned club |
| **Faculty/HOD** | Oversee all clubs, manage leads, view analytics | Administrative access to entire system |


---

## 🛠 Tech Stack  

#### **Frontend**  

[![React](https://img.shields.io/badge/React-000000?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-000000?style=for-the-badge&logo=tailwind-css&logoColor=06B6D4)](https://tailwindcss.com/)
[![Context API](https://img.shields.io/badge/Context_API-000000?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/reference/react/Context)

---

#### **Backend**  

[![Node.js](https://img.shields.io/badge/Node.js-000000?style=for-the-badge&logo=node.js&logoColor=339933)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io/)

---

#### **Database**  

[![MongoDB](https://img.shields.io/badge/MongoDB-000000?style=for-the-badge&logo=mongodb&logoColor=47A248)](https://www.mongodb.com/)
[![Mongoose](https://img.shields.io/badge/Mongoose-000000?style=for-the-badge&logo=mongoose&logoColor=880000)](https://mongoosejs.com/)

---

#### **Tools & Deployment**  

[![Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=F05032)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
[![Postman](https://img.shields.io/badge/Postman-000000?style=for-the-badge&logo=postman&logoColor=FF6C37)](https://www.postman.com/)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)
[![Render](https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=46E3B7)](https://render.com/)

---

#### **Code Editor**
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="40" height="40" title="VSCode" />

---

## 📦 Installation

### Prerequisites
```bash
# List your prerequisites
Node.js (v20 or higher)
npm 
MongoDB  (v5 or higher)
Git
```

### Clone Repository
```bash
git clone https://github.com/surendrapattikonda/Club-hub.git
cd club-hub
```

### Backend Setup
```bash
cd backend
npm install
# Create .env file with your configuration
cp .env.example .env

# Start development server
npm run dev
```

### Frontend Setup
```bash
cd frontend
npm install
# Start development server
npm run dev
```

### Environment Variables

Create a `.env` file in both frontend and backend directories:

**Backend `.env`:**
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000

```

**Frontend `.env`:**
```
VITE_API_URL=http://localhost:5000/api

```


---

## 🚀 Demo Access

To make testing quick and effortless, the application includes **one-click demo login buttons** on the Login page.

### 🔑 Available Demo Roles
- 🎓 **Student**
- 🧑‍💼 **Club Lead**
- 👨‍🏫 **Faculty**
- 🛡️ **Admin**

Each role auto-fills valid credentials instantly — **no manual typing required**.


> ⚠️ Demo credentials are for evaluation purposes only and are disabled in production deployments.

### Quick Start Guide

1. **As a Student**: Register → Browse Clubs → Request to Join → View Activities
2. **As a Club Lead**: Login → Approve Members → Create Activities → Mark Attendance
3. **As Faculty**: Login → View All Clubs → Analyze Metrics → Manage Leadership

---

## 🗄️ Database Schema <a id="database-schema"></a>

<details>
<summary><strong>Click to expand Database Schema</strong></summary>

```
┌─────────────────┐         ┌──────────────────┐         ┌─────────────────┐
│     Users       │         │      Clubs       │         │   Activities    │
├─────────────────┤         ├──────────────────┤         ├─────────────────┤
│ _id (PK)        │────┐    │ _id (PK)         │────┐    │ _id (PK)        │
│ name            │    │    │ name             │    │    │ title           │
│ email (unique)  │    │    │ description      │    │    │ description     │
│ regNo (unique)  │    │    │ leads[] (FK)     │◄───┘    │ date            │
│ password (hash) │    │    │ members[] (FK)   │         │ club (FK)       │
│ year (enum)     │    │    │ pendingMembers[] │         │ attendance[] (FK)│
│ role (enum)     │    │    │ facultyAdvisor   │         │ createdAt       │
│ clubs[] (FK)    │    │    │ createdAt        │         │ updatedAt       │
└─────────────────┘    │    │ updatedAt        │         └─────────────────┘
                       │    └──────────────────┘                 │
                       │            ▲                             │
                       │            │                             │
                       │            │ (embedded arrays)           │
                       │            │                             │
                       └────────────┴─────────────────────────────┘
                                    │
                                    │
                              ┌─────▼──────────┐
                              │   Attendance   │
                              ├────────────────┤
                              │ _id (PK)       │
                              │ activity (FK)  │
                              │ date           │
                              │ presentMembers│
                              │   [] (FK)      │
                              │ createdAt      │
                              │ updatedAt      │
                              └────────────────┘
```
</details>

---

## 📁 Project Structure

<details>
<summary><strong>Click to expand project structure</strong></summary>

```
CLUB-HUB/
│
├── backend/
│   ├── config/
│   │   └── db.js                 # Database configuration      
│   │
│   ├── controllers/
│   │   ├── activityController.js # Activity CRUD operations
│   │   ├── adminController.js    # Admin operations
│   │   ├── attendanceController.js
│   │   ├── authController.js     # Authentication logic
│   │   └── clubController.js     # Club CRUD operations
│   │
│   ├── middleware/
│   │   ├── authMiddleware.js     # JWT verification
│   │   └── roleMiddleware.js     # Role-based access control
│   │
│   ├── models/
│   │   ├── Activity.js
│   │   ├── Attendance.js
│   │   ├── Club.js
│   │   └── User.js
│   │
│   ├── routes/
│   │   ├── activityRoutes.js
│   │   ├── adminRoutes.js
│   │   ├── attendanceRoutes.js
│   │   ├── authRoutes.js
│   │   └── clubRoutes.js
│   │
│   ├── .env
│   ├── admin.js
│   ├── package.json
│   └── server.js                 # Entry point
│
├── frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── ProtectedRoute.tsx
│   │   ├── App.tsx
│   │   └── main.tsx
│   │
│   ├── public/
│   │   ├── index.html
│   │   └── favicon.ico
│   │
│   ├── package.json
│   └── vite.config.ts
│
├── screenshots/
├── README.md

```
</details>

---


## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---
## 🔮 Future Enhancements

- [ ] Mobile application (React Native)
- [ ] Email notification system
- [ ] Advanced analytics with data visualization
- [ ] Document management for club resources
- [ ] Integration with institutional calendar systems
- [ ] Real-time chat for club members

---



<div align="center">

### ⭐ Star this repository if you find it helpful!

**Made with ❤️ for streamlining student club management**

</div>
