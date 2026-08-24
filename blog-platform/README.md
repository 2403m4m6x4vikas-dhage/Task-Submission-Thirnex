# Blog Platform with Comments

Full-stack blogging platform with user authentication, blog post management and interactive comments.

## Features
- User registration and login with JWT
- Authentication middleware
- Create, edit and delete posts
- Public post listing and individual post view
- Add and delete comments
- Users can manage their own posts/comments
- RESTful Express APIs
- MySQL database schema
- Responsive frontend

## Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MySQL
Authentication: JWT + bcrypt

## Structure
- `frontend/` — responsive blog UI
- `backend/` — REST API
- `database/schema.sql` — MySQL schema

## Run
```bash
cd backend
npm install
npm start
```
Set `DB_HOST`, `DB_USER`, `DB_PASSWORD`, `DB_NAME`, and `JWT_SECRET` environment variables.
