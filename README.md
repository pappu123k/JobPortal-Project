# 💼 JobPortal – MERN Stack Job Hiring Platform

**JobPortal** is a full-featured job hiring platform where recruiters can post job listings, and candidates can search, apply, and manage their applications. Built using the MERN stack, it supports role-based authentication, secure APIs, resume uploads, and more.

---

## 🛠 Tech Stack

- 🌐 **MongoDB** – Database
- ⚙️ **Express.js** – Backend framework
- 🧠 **React.js** – Frontend library
- 🚀 **Node.js** – Server environment
- 🔐 **JWT** – Authentication and Authorization
- ☁️ **Cloudinary** – Resume and image uploads
- 📩 **Multer** – File upload handling

---

## 🔑 Key Features

### 👤 Authentication & Authorization
- User roles: **Candidate** and **Recruiter**
- Secure login/signup using JWT
- Protected routes with role-based access

### 🧑‍💼 Recruiter Dashboard
- Post new jobs with filters (location, experience, type)
- View and manage job listings
- Review candidate applications

### 🙋‍♂️ Candidate Dashboard
- Browse job listings with search and filters
- Apply to jobs (upload resume)
- Track applied jobs

### 📂 File Handling
- Resume/image uploads using **Multer** + **Cloudinary**
- Validation for allowed file types and size

### 🛡 Error Handling
- Global error handler for custom HTTP errors:
  - `404` – Not Found
  - `401` – Unauthorized
  - `400` – Bad Request
  - `500` – Server Error

---
