# Task Management Application

Full-stack task management project for creating, updating, tracking and deleting tasks.

## Features
- User registration and login with JWT authentication
- Password hashing with bcrypt
- Task CRUD REST API
- User-specific task access/authorization
- Status and priority tracking
- Responsive dashboard
- MySQL database schema

## Structure
- `backend/` — Node.js + Express API
- `frontend/` — HTML/CSS/JavaScript responsive client
- `database/schema.sql` — MySQL tables

## Run backend
```bash
cd backend
npm install
npm start
```
Set `DB_HOST`, `DB_USER`, `DB_PASSWORD`, `DB_NAME`, and `JWT_SECRET` in environment variables.

The frontend expects the API at `http://localhost:5000/api`.
