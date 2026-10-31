# 💊 PharmaDawa API

A secure, enterprise-ready RESTful API for pharmacy inventory management and point-of-sale (POS) operations, built with **Node.js**, **Express**, and **Better-SQLite3**.

---

## 🚀 Key Features

* **Advanced Security:** Secured HTTP headers via `Helmet`, custom CORS configuration, and payload size restriction (`10kb`).
* **Rate Limiting:** Global IP throttling and strict protection for sensitive endpoints (like login and checkout) to prevent brute-force and DoS attacks.
* **Authentication & RBAC:** JSON Web Token (JWT) based authentication with bcrypt password hashing and Role-Based Access Control.
* **Input Validation:** Robust request validation powered by `Joi`.
* **Database Reliability:** Uses `better-sqlite3` operating in **WAL (Write-Ahead Logging) mode** with atomic transactions for safe, concurrent sales processing and stock management.
* **Audit & Health Tracking:** Built-in health check endpoints and automated error-handling middleware.

---

## 🛠️ Prerequisites

Ensure you have the following installed on your machine:
* [Node.js](https://nodejs.org/) (v18+ recommended)
* npm (comes packaged with Node.js)

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/pharmadawa.git](https://github.com/your-username/pharmadawa.git)
   cd pharmadawa
   # PharmaDawa
