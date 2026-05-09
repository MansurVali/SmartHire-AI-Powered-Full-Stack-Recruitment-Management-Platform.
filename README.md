# SmartHire – Intelligent Recruitment Management Platform

> **Developed by D Mansur Vali**  
> Full Stack Developer | Java Enthusiast | Open to Opportunities  

[![GitHub](https://img.shields.io/badge/GitHub-MansurVali-black?style=for-the-badge&logo=github)](https://github.com/MansurVali)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/d-mansur-vali-4a3b68262)

---

## Project Overview

SmartHire is a modern AI-powered full-stack recruitment platform designed to simplify and automate the hiring process for organizations. It enables recruiters to manage job postings, screen candidates, track applications, and improve hiring efficiency through a secure and scalable system.

Built with enterprise-grade architecture using Java Spring Boot, React.js, PostgreSQL, JWT Authentication, and REST APIs.

---

## Key Features

- Secure Role-Based Authentication (Admin / Recruiter / Candidate)
- Recruiter Dashboard for Job & Candidate Management
- Candidate Job Search and Application Tracking
- Resume Screening & Smart Candidate Ranking
- Real-Time Hiring Updates and Notifications
- RESTful API Integration with Spring Boot
- Responsive UI with React.js & Modern CSS
- Multi-tenant Scalable Architecture
- PostgreSQL Database with Optimized Queries

---

## Tech Stack

| Layer | Technologies |
|------|-------------|
| Frontend | React.js, JavaScript, HTML5, CSS3 |
| Backend | Java, Spring Boot, Spring Security |
| Database | PostgreSQL, Hibernate / JPA |
| Security | JWT Authentication, BCrypt |
| APIs | REST APIs |
| Tools | Maven, Git, GitHub, Postman |

---

## System Architecture

```text
Frontend (React.js)
      ↓
REST APIs
      ↓
Backend (Spring Boot)
      ↓
Hibernate / JPA
      ↓
PostgreSQL Database
```

---

## Screenshots

### Login Page
![Login Page](https://app.devin.ai/attachments/2d4ca574-29ce-4797-9ac1-7d7f04d1a6e8/01-login-page.png)

### Hiring Dashboard (Acme Corp – Admin)
![Dashboard](https://app.devin.ai/attachments/9e96a3f5-2ad6-49ee-a5ae-e1e41ace060e/02-dashboard.png)

### Job Postings
![Job Postings](https://app.devin.ai/attachments/e11beceb-d97d-4f00-8ef4-d61b13b2261b/03-job-postings.png)

### Candidate Pipeline
![Pipeline](https://app.devin.ai/attachments/03480018-4fb7-4a63-9a55-5fef84c50b0d/04-pipeline.png)

### Live AI Screening
![Live AI Screening](https://app.devin.ai/attachments/d7d7136a-d62c-4065-a096-e91df78f095c/05-live-ai-screening.png)

### Register Company
![Register Company](https://app.devin.ai/attachments/203b54bb-08ec-4182-bfb6-abf7f25144b0/06-register-company.png)

### Multi-Tenant Isolation (NexGen Tech – Recruiter)
![NexGen Dashboard](https://app.devin.ai/attachments/f42c0a00-b977-4a03-af4d-3acd8017cf66/07-nexgen-dashboard.png)

---

## Getting Started

### Prerequisites

- **Java 21** (e.g. Temurin `21.0.4-tem` via [SDKMAN](https://sdkman.io/))
- **Maven 3.8+**
- **Node.js 18+** and **npm**
- **PostgreSQL 14+**

### 1. Clone the Repository

```bash
git clone https://github.com/MansurVali/SmartHire-AI-Powered-Full-Stack-Recruitment-Management-Platform..git
cd SmartHire-AI-Powered-Full-Stack-Recruitment-Management-Platform.
```

### 2. Set Up the Database

```bash
# Start PostgreSQL and create the database
sudo -u postgres psql -c "CREATE DATABASE smarthire_db;"
sudo -u postgres psql -c "ALTER USER postgres WITH PASSWORD 'root';"

# Seed the schema and demo data
sudo -u postgres psql -d smarthire_db -f database/schema.sql
```

### 3. Build & Run the Backend

```bash
cd backend
mvn clean package -DskipTests
java -jar target/smarthire-backend-1.0.0.jar
```

The backend starts on **http://localhost:8080**.

### 4. Run the Frontend

```bash
cd frontend
npm install
npm run dev
```

The frontend starts on **http://localhost:3000**.

### 5. Login with Demo Credentials

| Tenant | Email | Password | Role |
|--------|-------|----------|------|
| `acme-corp` | `admin@acme.com` | `password123` | ADMIN |
| `nexgen-tech` | `bob@nexgen.com` | `password123` | RECRUITER |

### Optional: AI Resume Scoring

To enable full Claude AI-powered resume scoring, set the environment variable before starting the backend:

```bash
export ANTHROPIC_API_KEY=your-api-key-here
```

Without the API key, the app falls back to keyword-based scoring.

---

## Project Structure

```text
SmartHire/
├── backend/                 # Spring Boot application
│   ├── src/main/java/       # Java source code
│   ├── src/main/resources/  # application.yml, static assets
│   └── pom.xml              # Maven dependencies
├── frontend/                # React + Vite application
│   ├── src/                 # React components, pages, hooks
│   └── package.json         # npm dependencies
├── database/
│   └── schema.sql           # PostgreSQL schema + seed data
└── README.md
```

---

## Contact

**D Mansur Vali**  
- GitHub: [MansurVali](https://github.com/MansurVali)  
- LinkedIn: [d-mansur-vali](https://linkedin.com/in/d-mansur-vali-4a3b68262)  
- Email: dmanu9512@gmail.com
