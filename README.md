# Project Name

This project is a **full-stack application** built with React (frontend), NestJS (backend), and PostgreSQL (database). It includes user authentication/login functionality and follows modern best practices.

---

## Table of Contents
- [Login](#login)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Database Setup](#database-setup)
- [License](#license)

---

## Login

The application supports **user login** with the following features:

- **Email and Password authentication**
- **JWT-based authentication** for secure API access
- **Role-based access control (optional)**
- Error handling and validation for login forms
- Password hashing using `bcrypt` or similar libraries

### Login Endpoint (Backend)
```http
POST /auth/login

{
  "email": "admin@gmail.com",
  "password": "india@12345"
}


