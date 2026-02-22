# 🚀 CareerGenie – Smart Resume Analyzer & Job Matcher

CareerGenie is an AI-powered full-stack web application that analyzes resumes, provides intelligent feedback, and matches users with relevant job opportunities.

It combines resume parsing, AI-based evaluation, job matching algorithms, and role-based dashboards into one unified platform.

---

## 🧠 Overview

CareerGenie helps job seekers:

- Upload their resume
- Get AI-based improvement suggestions
- Receive skill gap analysis
- Match with relevant job roles
- Track applications via dashboard

The system uses AI models for resume evaluation and a structured matching engine for job recommendations.

---

## 🏗️ Tech Stack

### 🔹 Frontend
- React.js
- TailwindCSS
- Axios
- React Router
- JWT Authentication Handling

### 🔹 Backend
- Node.js
- Express.js
- MongoDB (or PostgreSQL)
- JWT Authentication
- Multer (file upload handling)

### 🔹 AI Integration
- Resume parsing logic
- Skill extraction
- AI-based resume feedback
- Job matching algorithm (skill similarity scoring)

---

## 📐 System Architecture

```
User → React Frontend
        ↓
Authentication (JWT)
        ↓
Resume Upload (PDF/DOC)
        ↓
Backend Processing (Node + Express)
        ↓
Resume Parsing & Skill Extraction
        ↓
AI Feedback Generation
        ↓
Job Matching Engine
        ↓
Dashboard Display
```

---

## ✨ Core Features

### 📄 Resume Analyzer
- Upload resume (PDF/DOC)
- Extract skills and experience
- AI-based suggestions for improvement
- Identify missing keywords

### 🎯 Job Matching Engine
- Compare user skills with job requirements
- Score-based matching
- Return top relevant job listings

### 👤 Role-Based Dashboards
- User dashboard
- Admin dashboard
- Resume history tracking
- Application tracking

### 🔐 Authentication & Authorization
- JWT-based authentication
- Secure protected routes
- Role-based access control

---

## ⚙️ How It Works

### 1️⃣ Resume Upload
User uploads a resume file.

### 2️⃣ Parsing
Backend extracts:
- Skills
- Education
- Experience
- Keywords

### 3️⃣ AI Feedback
System analyzes:
- Skill gaps
- Weak sections
- Missing keywords
- Optimization suggestions

### 4️⃣ Job Matching
- Job database contains structured requirements
- Skills are compared
- Matching score calculated
- Top matches returned

---

## 🛠️ How to Run Locally

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/career-genie.git
cd career-genie
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```
PORT=5000
MONGO_URI=your_database_connection
JWT_SECRET=your_secret
OPENAI_API_KEY=your_key
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

Frontend runs on:
```
http://localhost:3000
```

Backend runs on:
```
http://localhost:5000
```

---

## 📊 Matching Algorithm (Concept)

Matching score is calculated using:

- Skill overlap percentage
- Keyword match frequency
- Experience alignment
- Role-based weight distribution

Future enhancement:
- Vector-based similarity search
- AI-driven semantic job matching

---

## 📌 Assumptions & Limitations

- Resume parsing is rule-based (not fully semantic)
- No real-time job scraping
- Matching is keyword-driven (not embedding-based)
- No microservices architecture
- Limited scalability (single-instance backend)

---

## 🔮 Future Improvements

- Integrate vector embeddings for semantic job matching
- Add recruiter portal
- Implement resume scoring system
- Add analytics dashboard
- Deploy using Docker + CI/CD
- Cloud deployment (AWS / Render / Vercel)

---

## 🎯 Key Learnings

- Full-stack architecture design
- JWT authentication implementation
- File upload and parsing pipeline
- AI integration into web applications
- Building scalable dashboards
- Structuring production-ready backend APIs

---

## 📜 License

This project is built for academic and portfolio purposes.
