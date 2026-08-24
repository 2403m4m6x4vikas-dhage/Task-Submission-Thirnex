# E-Commerce Web Application

Full-stack online store project with product catalog, cart, checkout flow, authentication, role-based access and order management.

## Features
- Product catalog and search
- Add to cart / quantity management
- Checkout and order creation
- User registration/login with JWT
- Admin/User role-based access
- Product CRUD APIs for admins
- Order APIs and order tracking
- MySQL database schema
- Responsive storefront UI

## Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MySQL
Authentication: JWT + bcrypt

## Structure
- `frontend/` responsive storefront
- `backend/` REST API
- `database/schema.sql` database schema

## Run backend
```bash
cd backend
npm install
npm start
```
Configure `DB_HOST`, `DB_USER`, `DB_PASSWORD`, `DB_NAME`, and `JWT_SECRET` environment variables.
