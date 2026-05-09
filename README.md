# 🚀 SmartHire – AI Powered Full Stack Recruitment Management Platform

<div align="center">

![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge\&logo=java)
![Spring Boot](https://img.shields.io/badge/SpringBoot-3.x-brightgreen?style=for-the-badge\&logo=springboot)
![React](https://img.shields.io/badge/React.js-Frontend-61DAFB?style=for-the-badge\&logo=react)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge\&logo=postgresql)
![JWT](https://img.shields.io/badge/JWT-Authentication-black?style=for-the-badge\&logo=jsonwebtokens)
![REST API](https://img.shields.io/badge/REST-API-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Active-success?style=for-the-badge)

### 💼 Enterprise-Level Full Stack Recruitment Management Platform

*An AI-driven recruitment ecosystem built using Java Spring Boot, React.js, PostgreSQL, JWT Authentication, and REST APIs for secure and scalable hiring operations.*

</div>

---

# 📌 Project Overview

SmartHire is a modern full-stack recruitment management platform designed to simplify and automate the hiring lifecycle for companies, recruiters, and candidates.

The platform enables:

* 🏢 Companies to manage recruitment workflows
* 👨‍💼 Recruiters to post jobs and track applicants
* 👨‍🎓 Candidates to apply for opportunities
* 🤖 AI-powered screening for smart candidate evaluation
* 🔐 Secure authentication using JWT and Spring Security
* 📊 Dashboard-based hiring analytics and management

This project demonstrates real-world enterprise application development using scalable backend architecture and modern frontend technologies.

---

# ✨ Key Features

## 🔐 Authentication & Security

* JWT-based Authentication
* Role-Based Access Control (RBAC)
* Secure Login & Registration
* Spring Security Integration
* Password Encryption using BCrypt
* Session Management

## 👨‍💼 Recruiter Features

* Create & Manage Job Postings
* View Candidate Applications
* Candidate Pipeline Tracking
* AI Screening Dashboard
* Recruitment Workflow Automation
* Company Registration Management

## 👨‍🎓 Candidate Features

* Browse Available Jobs
* Apply for Jobs
* Resume Submission
* Track Application Status
* Profile Management

## 🏢 Admin Features

* Manage Recruiters & Companies
* System Monitoring Dashboard
* Multi-Tenant Management
* Access Control
* Data Management

## 🤖 AI Features

* Resume Screening
* Candidate Ranking
* Intelligent Filtering
* Smart Hiring Workflow

---

# 🛠️ Tech Stack

| Category        | Technologies                       |
| --------------- | ---------------------------------- |
| Frontend        | React.js, JavaScript, HTML5, CSS3  |
| Backend         | Java, Spring Boot, Spring Security |
| Database        | PostgreSQL                         |
| Authentication  | JWT Authentication                 |
| API             | RESTful APIs                       |
| ORM             | JPA / Hibernate                    |
| Build Tool      | Maven                              |
| Version Control | Git & GitHub                       |
| IDE             | VS Code / IntelliJ IDEA            |

---

# 🧠 System Architecture

```text
Frontend (React.js)
        ↓
REST APIs
        ↓
Spring Boot Backend
        ↓
Service Layer
        ↓
JPA / Hibernate
        ↓
PostgreSQL Database
```

---

# 📂 Project Structure

```text
SmartHire/
│
├── backend/
│   ├── src/main/java
│   ├── controller
│   ├── service
│   ├── repository
│   ├── entity
│   └── security
│
├── frontend/
│   ├── src
│   ├── components
│   ├── pages
│   ├── redux
│   └── services
│
├── database/
│   └── schema.sql
│
├── screenshots/
│
└── README.md
```

---

# 📸 Application Screenshots

## 🔑 Login Page

![Login Page](./screenshots/login-page.png)

### Features

* Secure JWT Authentication
* User Login Validation
* Responsive UI Design
* Role-Based Access

---

## 📊 Hiring Dashboard (Admin)

![Dashboard](./screenshots/dashboard.png)

### Dashboard Capabilities

* Recruiter Management
* Analytics Overview
* Candidate Monitoring
* Hiring Workflow Insights

---

## 💼 Job Postings Module

![Job Postings](./screenshots/job-postings.png)

### Features

* Create Jobs
* Edit Job Listings
* Manage Open Positions
* Track Applicants

---

## 👨‍💻 Candidate Pipeline

![Pipeline](./screenshots/pipeline.png)

### Features

* Candidate Tracking
* Recruitment Stages
* Interview Workflow
* Application Monitoring

---

## 🤖 Live AI Screening

![Live AI Screening](./screenshots/live-ai-screening.png)

### Features

* AI Candidate Analysis
* Resume Filtering
* Smart Ranking
* Hiring Recommendations

---

## 🏢 Register Company Module

![Register Company](./screenshots/register-company.png)

### Features

* Company Onboarding
* Recruiter Registration
* Multi-Tenant Support
* Validation & Security

---

## 🌐 Multi-Tenant Recruiter Dashboard

![NexGen Dashboard](./screenshots/nexgen-dashboard.png)

### Features

* Tenant Isolation
* Recruiter Management
* Organization Control
* Secure Access Management

---

# ⚙️ Backend Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/SmartHire.git
```

---

## 2️⃣ Navigate to Backend

```bash
cd backend
```

---

## 3️⃣ Configure PostgreSQL

Update:

```text
src/main/resources/application.yml
```

Example:

```yaml
spring:
  datasource:
    url: jdbc:postgresql://localhost:5432/smarthire
    username: postgres
    password: your_password
```

---

## 4️⃣ Run Backend

```bash
mvn spring-boot:run
```

Server runs on:

```text
http://localhost:8080
```

---

# 💻 Frontend Setup

## Navigate to Frontend

```bash
cd frontend
```

## Install Dependencies

```bash
npm install
```

## Run Frontend

```bash
npm run dev
```

Frontend runs on:

```text
http://localhost:5173
```

---

# 🗄️ PostgreSQL Setup

## Create Database

```sql
CREATE DATABASE smarthire;
```

## Open pgAdmin

* Create server connection
* Use port: 5432
* Username: postgres
* Enter your PostgreSQL password

---

# 🔌 REST API Highlights

| API                | Description          |
| ------------------ | -------------------- |
| /api/auth/login    | User Login           |
| /api/auth/register | User Registration    |
| /api/jobs          | Job Management       |
| /api/candidates    | Candidate Operations |
| /api/recruiters    | Recruiter Management |
| /api/admin         | Admin Dashboard      |

---

# 🔐 Security Features

* Spring Security
* JWT Token Authentication
* BCrypt Password Hashing
* Protected Routes
* Secure API Access
* Authentication Filters

---

# 📈 Future Enhancements

* 🔍 Advanced AI Resume Matching
* 📧 Email Notifications
* 📹 Video Interview Integration
* ☁️ Cloud Deployment
* 📊 Analytics Dashboard
* 🧠 Machine Learning Recommendations
* 📱 Mobile Application
* 🌍 Multi-Language Support

---

# 🏆 Learning Outcomes

This project demonstrates:

* Enterprise Backend Development
* Secure Authentication Systems
* REST API Design
* Full Stack Integration
* Database Management
* Frontend State Management
* Recruitment Workflow Automation
* Real-World Software Architecture

---

# 👨‍💻 Author

## Mansur Vali

### Java Full Stack Developer

* Java
* Spring Boot
* React.js
* PostgreSQL
* REST APIs
* JWT Authentication
* Full Stack Development

### 📬 Connect With Me

* GitHub: [https://github.com/](https://github.com/)
* LinkedIn: [https://linkedin.com/](https://linkedin.com/)

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository
🍴 Fork the project
📢 Share with others

---

<div align="center">

# 🚀 SmartHire

### Transforming Recruitment with AI & Full Stack Technology

💼 Built with Passion using Java Spring Boot & React.js

</div>
