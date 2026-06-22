<h1 align="center">🚀 Internship & Trainee Recruitment Platform</h1>

<p align="center">
Full Stack Enterprise System built with Angular & ASP.NET Core using Clean Architecture principles.
</p>

---

## 🎥 Live Preview

<p align="center">
  <img src="./assets/demo.gif" width="900" />
</p>

---

## 📌 About The Project

This is a full-stack recruitment platform that connects:

- 🎓 Students & Graduates
- 🏢 Employers & Companies
- 🏫 Universities

It manages internships, applications, and hiring workflow in one system.

---

## ⚙️ Features

### 🔐 Authentication
- JWT Authentication
- Refresh Tokens
- Role-Based Access (Admin / Employer / Candidate)
- Password Reset & Email Verification

### 🎓 Candidate Module
- Profile Management
- CV Upload
- Apply for Internships
- Track Applications

### 🏢 Employer Module
- Company Profile
- Post Internships
- Manage Applicants
- Shortlisting System

### 📢 Internship System
- Search & Filters
- Categories
- Pagination

### 📊 Admin Panel
- User Management
- Analytics Dashboard
- Platform Monitoring

---

## 🧠 Architecture

```txt id="arch_clean"
Angular Frontend
        ↓
ASP.NET Core Web API
        ↓
Application Layer (CQRS)
        ↓
Domain Layer (Business Rules)
        ↓
Infrastructure Layer (EF Core)
        ↓
SQL Server
