# Blog Platform

This is a blog platform project that I built using React, Node.js and PostgreSQL.
The main idea was to understand how frontend, backend and database work together in a real project.

---

## ✨ Features

* Create blog posts
* Edit posts
* Delete posts
* Add comments
* Simple dark UI

---

## 🏗️ Architecture

Frontend (React) → Backend (Node.js + Express) → Database (PostgreSQL)

---

## 📁 Project Structure

* frontend → React UI
* backend → API using Node.js
* deploy → scripts for deployment

---

## 🚀 Deployment

I deployed this project on AWS EC2.

Steps I followed:

* Created EC2 instance
* Transferred files using SCP
* Ran setup script
* Configured Nginx
* Started backend using PM2

Then accessed using public IP.

---

## 💻 Local Setup

### Backend

```bash
cd backend
npm install
npm start
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 📡 API

* GET posts
* POST create post
* PUT update post
* DELETE post
* Comments APIs

---

## 🌿 Branches

* main → basic project
* devops → added DevOps tools like Docker, Kubernetes and CI/CD

---

## 🧠 What I Learned

* How full stack apps work
* Connecting frontend with backend
* Working with PostgreSQL
* Basic deployment on AWS

---

This project helped me understand real-world application flow.
