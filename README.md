# 🏥 Hospital Management System

A full-stack MERN web application for managing core hospital operations: doctors and patients, appointments and medical records, billing and pharmacy, and laboratory and nursing, with authentication.

![React](https://img.shields.io/badge/frontend-React%20%2B%20Vite-61DAFB)
![Node](https://img.shields.io/badge/backend-Node.js%20%2B%20Express-339933)
![MongoDB](https://img.shields.io/badge/database-MongoDB-47A248)

## ✨ Features

- 🔐 Authentication
- 👨‍⚕️ Doctor and patient management
- 📅 Appointments and medical records
- 💊 Billing and pharmacy
- 🧪 Laboratory and nursing modules
<!-- [AI] If you have an AI feature, add it here, e.g. - 🤖 Symptom-based department suggestion -->

## 🛠 Tech Stack

| Category | Technologies |
|---|---|
| Frontend | React.js, Vite |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Language | JavaScript |
| API Communication | Axios, REST API |
| Routing | React Router DOM |
| Configuration | dotenv |
| Middleware | CORS |
| Code Quality | ESLint |
| Version Control | Git and GitHub |

## 🏗 Architecture

```mermaid
flowchart TD
    U[User] --> F[React Frontend]
    F <-->|REST API / Axios| B[Express.js Backend]
    B <--> D[(MongoDB)]
    B --> A[Authentication]
    B --> M[Hospital Management Modules]
    M --> M1[Doctors and Patients]
    M --> M2[Appointments and Medical Records]
    M --> M3[Billing and Pharmacy]
    M --> M4[Laboratory and Nursing]
```

## 📁 Project Structure

```
├── backend/     # Express.js API, models, routes
├── frontend/    # React + Vite client
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or later)
- MongoDB (local or Atlas)

### Setup

```bash
git clone https://github.com/Zihad-098/AI-Hospital-Management-System.git
cd AI-Hospital-Management-System
```

**Backend**
```bash
cd backend
npm install
```
Create a `.env` file in `backend/`:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret
```
```bash
npm start
```

**Frontend**
```bash
cd frontend
npm install
npm run dev
```

## 🖼 Screenshots
<!-- Add 3-4 screenshots: login, dashboard, appointments, billing -->

## 🗺 Future Improvements
<!-- Add real ones, e.g. role-based access, AI features, deployment -->

## 👨‍💻 Author
**Zihad Hossen** · [GitHub](https://github.com/Zihad-098)
