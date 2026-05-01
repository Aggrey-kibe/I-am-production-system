# IAM Production System (Enterprise-Grade)

A fully structured, production-ready Identity & Access Management (IAM) system designed with real-world enterprise security, scalability, and maintainability principles.

Built using Node.js, Express, MongoDB, and Redis with a clean layered architecture.

---

## 🚀 System Overview

This system provides a secure authentication and authorization framework including:

- JWT Authentication (Access + Refresh tokens)
- Role-Based Access Control (RBAC)
- Secure session management using Redis
- Email verification system
- Password reset flow
- Audit logging for all critical actions
- Rate limiting and security hardening

---

## 🏗️ Architecture (Enterprise Standard)



Separation ensures:
- Scalability
- Testability
- Maintainability
- Clean business logic isolation

---

## 🔐 Features

### Authentication
- User registration
- Login/logout system
- JWT access tokens (short-lived)
- Refresh token rotation (secure sessions)
- HTTP-only cookie support (production-ready approach)

### Authorization
- Role-Based Access Control (RBAC)
- Permission-based middleware support
- Admin/User separation

### Security Layer
- Helmet (HTTP security headers)
- Rate limiting (brute-force protection)
- Input validation (Joi)
- Secure password hashing (bcrypt)
- Token expiration + rotation

### Email System
- Email verification after signup
- Password reset via secure token
- Expiring email tokens

### Audit System
- Logs login attempts
- Tracks user actions
- Stores security events in database

---

## 📁 Project Structure



---

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB (Mongoose)
- Redis (session storage)
- JWT Authentication
- Nodemailer
- Docker

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/iam-production-system.git
cd iam-production-system
npm install




MONGO_URI=
JWT_SECRET=
REDIS_URL=
EMAIL_USER=
EMAIL_PASS=
NODE_ENV=production

npm start


docker-compose up --build
