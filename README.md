### ℹ️ About This Project

All original code is licensed under the [MIT License](LICENSE).

This project is based on the **[Advanced Auth Tutorial](https://youtu.be/pmvEgZC55Cg)** by [Burak](https://github.com/burakorkmez).  
I made adjustments and updates to ensure compatibility with newer versions of Node, Vite, and deployment platforms.

### 🟢 Project Name: GreenVault

The name "GreenVault" reflects the green-themed UI of the app and its purpose as a secure authentication system.

This is a full-stack authentication system built with **Node.js**, **Express**, **MongoDB**, and **React**.  
It includes all essential auth features and a clean UI, covering both backend and frontend.

### ✅ Features Implemented

- 🔧 Backend Setup
- 🗄️ Database Configuration
- 🔐 Signup Endpoint
- 📧 Email Verification
- 🔍 Verify Email Endpoint
- 📄 Welcome Email Template
- 🚪 Logout Endpoint
- 🔑 Login Endpoint
- 🔄 Forgot Password Flow
- 🔁 Reset Password Endpoint
- ✔️ Auth Check Middleware
- 🌐 Frontend Setup with React + Vite
- 📋 Signup Page UI
- 🔓 Login Page UI
- ✅ Email Verification UI
- 🏠 Dashboard Page
- 🔒 Protected Routes
- 🔄 Forgot/Reset Password Integration
- 🚀 Deployment Guide

---

## ⚙️ Environment Setup

Create a `.env` file in the root of the backend folder and configure as the following example:

MONGO_URI=your_mongo_uri
PORT=5000
JWT_SECRET=your_secret_key
NODE_ENV=development

MAILTRAP_TOKEN=your_mailtrap_token

CLIENT_URL=http://localhost:5173

---

## 📨 This project uses Mailtrap to send emails in development mode

You have two options:

✅ Use the Mailtrap Sandbox domain

    - Allows sending emails only to your own verified Mailtrap email address

    - Limited to 20 emails on the free plan

🌐 Use a Custom Domain

    - Allows sending emails to any address

    - Requires domain setup and DNS verification on Mailtrap

For local testing, the sandbox is usually sufficient.
