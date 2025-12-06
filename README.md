## 🚀RESUMIND: AI Resume Analyzer (React + TypeScript + Puter.js)

An intelligent resume-analysis web application that extracts text from PDF resumes, processes it using AI (via Puter.js), and displays structured insights such as candidate name, job role, skills, experience, projects, and improvement suggestions.

This project is fully frontend-driven and uses **Puter.js** as the backend service for:
- File uploads  
- Fetching PDF content  
- Storage  
- Processing  

---

## ⭐ Features

🔍 AI-based resume text analysis

📤 PDF upload + automatic text extraction

🧠 Generates structured resume insights

🧾 Dynamic resume result pages (/resume/:id)

☁️ Puter.js backend for file handling & AI processing

⚡ React + TypeScript + Vite frontend

---

## 🛠 Tech Stack

### **Frontend**
- React + TypeScript
- React Router DOM
- Tailwind / CSS (your choice)
- Vite
- Axios

### **Backend (Serverless using Puter)**
- Puter.js  
- AI Model Provider: _(OpenAI / Gemini / Puter AI — whatever you used)_

---

## Folder Structure
AI-Resume-Analyser/
│
├── app/
│   ├── Components/
│   │   └── ResumePage.tsx
│   ├── routes/
│   │   ├── home.tsx
│   │   ├── auth.tsx
│   │   ├── upload.tsx
│   │   └── resume.$id.tsx
│   ├── welcome/
│   └── app.css
│
├── public/
├── constants/
├── types/
├── Dockerfile
├── package.json
├── react-router.config.ts
├── README.md
├── tsconfig.json
└── vite.config.ts

