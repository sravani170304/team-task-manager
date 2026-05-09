Team Task Manager

Team Task Manager is a modern full-stack collaboration platform developed to simplify project and task management for teams and organizations. The application allows admins to manage projects, assign tasks, monitor progress, and analyze productivity through interactive dashboards, while members can update assigned tasks and track deadlines efficiently.

Key Features:
Secure Authentication (JWT)
Role-Based Access Control
Project & Team Management
Task Assignment & Tracking
Dashboard Analytics
Responsive UI
Live Deployment

Tech Stack:
React.js
Tailwind CSS
Node.js
Express.js
MongoDB Atlas

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
git clone <your-github-repo-link>
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
