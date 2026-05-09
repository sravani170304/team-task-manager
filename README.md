# Team Task Manager

## Project Overview
Team Task Manager is a modern full-stack collaboration platform developed to simplify project and task management for teams and organizations. The application allows admins to manage projects, assign tasks, monitor progress, and analyze productivity through interactive dashboards, while members can update assigned tasks and track deadlines efficiently.

---

# Live Demo
https://sravani123.lovable.app

---

# Key Features
- Secure Authentication using JWT
- Role-Based Access Control (Admin/Member)
- Project & Team Management
- Task Assignment & Progress Tracking
- Interactive Dashboard Analytics
- Responsive User Interface
- Live Deployment

---

# Tech Stack

## Frontend
- React.js
- Tailwind CSS
- Axios
- React Router

## Backend
- Node.js
- Express.js

## Database
- MongoDB Atlas

## Authentication
- JWT Authentication
- bcrypt Password Hashing

---

# Folder Structure

## Frontend
```bash
src/
 ├── components/
 ├── pages/
 ├── services/
 ├── context/
 ├── hooks/
 └── layouts/
```

## Backend
```bash
server/
 ├── controllers/
 ├── models/
 ├── routes/
 ├── middleware/
 ├── config/
 └── utils/
```

---

# Installation

## Clone Repository
```bash
git clone <https://github.com/sravani170304/team-task-manager>
```

## Install Frontend Dependencies
```bash
npm install
```

## Install Backend Dependencies
```bash
cd server
npm install
```

## Run Frontend
```bash
npm run dev
```

## Run Backend
```bash
npm start
```

---

# Environment Variables

Create a `.env` file inside the `server` folder and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

# Features Explanation

## Authentication
The application uses JWT-based authentication with encrypted passwords using bcrypt to ensure secure login and signup functionality.

## Role-Based Access Control
Two roles are implemented:
- Admin
- Member

Admins can manage projects and tasks, while members can update assigned tasks and track progress.

## Project Management
Admins can:
- Create projects
- Assign team members
- Set deadlines
- Track project progress

## Task Management
Users can:
- Create tasks
- Assign tasks
- Update task status
- Monitor deadlines

Task statuses include:
- Pending
- In Progress
- Completed
- Overdue

## Dashboard
Interactive dashboard provides:
- Total tasks
- Project statistics
- Task progress analytics
- Productivity tracking

---

# API Endpoints

## Authentication APIs
- POST `/api/auth/signup`
- POST `/api/auth/login`

## Project APIs
- GET `/api/projects`
- POST `/api/projects`
- PUT `/api/projects/:id`
- DELETE `/api/projects/:id`

## Task APIs
- GET `/api/tasks`
- POST `/api/tasks`
- PUT `/api/tasks/:id`
- DELETE `/api/tasks/:id`

---

# Deployment

## Frontend
Deployed using Lovable

## Backend
Deployed using Railway

## Database
MongoDB Atlas Cloud Database

---

# Future Enhancements
- Real-time notifications
- Team chat integration
- File upload support
- Calendar integration
- AI-based productivity analytics

---

# Author
**Kakaraparthi Sravani**
