<div align="center">

# 🤖 AI Recruitr
### AI-Powered Resume Analyzer & ATS Score Checker

<p align="center">
Analyze resumes, evaluate ATS compatibility, extract resume insights, and receive intelligent feedback to improve your chances of landing interviews.
</p>

<p align="center">

![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript)
![React Router](https://img.shields.io/badge/React_Router-v7-CA4245?style=for-the-badge&logo=reactrouter)
![Vite](https://img.shields.io/badge/Vite-6-646CFF?style=for-the-badge&logo=vite)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-38B2AC?style=for-the-badge&logo=tailwindcss)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</p>

---

### 🚀 Upload • Analyze • Optimize • Get Interview Ready

</div>

---

# 📖 About

**AI Recruitr** is an AI-powered resume analysis platform that helps job seekers evaluate their resumes against modern Applicant Tracking Systems (ATS).

Users can upload a PDF resume, receive an ATS compatibility score, identify missing skills, review resume quality, and obtain actionable suggestions to improve their chances of getting shortlisted.

The application combines modern frontend technologies with intelligent resume parsing to deliver a fast and interactive user experience.

---

# ✨ Features

- 📄 Upload Resume (PDF)
- 🤖 AI Resume Analysis
- 📊 ATS Compatibility Score
- 🎯 Resume Quality Evaluation
- 📝 Intelligent Feedback & Suggestions
- 📑 PDF Preview
- ☁️ Cloud Storage Integration
- ⚡ Fast React Router v7 Architecture
- 📱 Responsive UI
- 🎨 Modern Dashboard Design

---

# 🛠 Tech Stack

| Frontend | State Management | Utilities |
|-----------|-----------------|-----------|
| React 19 | Zustand | PDF.js |
| TypeScript | React Router v7 | React Dropzone |
| Vite | React Hooks | Tailwind Merge |
| Tailwind CSS | Context API | clsx |

---

# 📂 Project Structure

```text
ai-recruitr/
│
├── app/
│   ├── components/
│   │   ├── ATS.tsx
│   │   ├── Accordion.tsx
│   │   ├── FileUploader.tsx
│   │   ├── ResumeCard.tsx
│   │   ├── ScoreGauge.tsx
│   │   ├── ScoreCircle.tsx
│   │   └── Summary.tsx
│   │
│   ├── routes/
│   │   ├── home.tsx
│   │   ├── upload.tsx
│   │   ├── resume.tsx
│   │   ├── auth.tsx
│   │   └── wipe.tsx
│   │
│   ├── lib/
│   │   ├── pdf2image.ts
│   │   ├── utils.ts
│   │   └── puter.ts
│   │
│   ├── constants/
│   ├── public/
│   └── root.tsx
│
├── Dockerfile
├── package.json
└── README.md
```

---

# 🚀 Application Workflow

```text
User Uploads Resume (PDF)
            │
            ▼
     PDF Processing
            │
            ▼
 Resume Content Extraction
            │
            ▼
 AI Resume Analysis
            │
            ▼
 ATS Compatibility Check
            │
            ▼
 Resume Score Generation
            │
            ▼
 Personalized Suggestions
```

---

# 📈 ATS Analysis Includes

- ATS Compatibility Score
- Resume Formatting
- Keyword Optimization
- Content Quality
- Section Analysis
- Resume Strengths
- Improvement Suggestions
- Overall Resume Rating

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/asyncShaurya/ai-recruitr.git
```

Move into the project

```bash
cd ai-recruitr
```

Install dependencies

```bash
npm install
```

Run development server

```bash
npm run dev
```

Build production

```bash
npm run build
```

Run production

```bash
npm start
```

---

# ⚙️ Available Scripts

```bash
npm run dev
```

Starts the development server.

```bash
npm run build
```

Builds the production application.

```bash
npm run start
```

Starts the production server.

```bash
npm run typecheck
```

Generates route types and checks TypeScript errors.

---

# 💡 Key Components

### 📄 Resume Upload

Drag & Drop PDF upload with instant preview.

---

### 🤖 ATS Analyzer

Evaluates resumes against Applicant Tracking System standards.

---

### 📊 Resume Score Dashboard

Displays

- ATS Score
- Resume Quality
- Skill Match
- Improvement Areas

---

### 📝 AI Feedback

Provides personalized recommendations to improve the resume.

---

### 📂 PDF Rendering

Built using PDF.js for seamless resume preview.

---

# 🎯 Learning Outcomes

This project helped me gain practical experience with:

- React Router v7
- TypeScript
- Vite
- Resume Parsing
- PDF Processing
- State Management with Zustand
- AI-powered UI Design
- ATS Optimization Concepts
- Component-Based Architecture

---

# 🔮 Future Improvements

- OpenAI-powered Resume Suggestions
- Job Description Matching
- Skill Gap Analysis
- Cover Letter Generator
- Resume Version History
- Resume Templates
- Authentication
- Resume Export
- Dark Mode
- Multi-language Support

---
# 🐳 Docker

Build Docker Image

```bash
docker build -t ai-recruitr .
```

Run Container

```bash
docker run -p 3000:3000 ai-recruitr
```

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository

2. Create your feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 👨‍💻 Author

## Shaurya Singh

Final Year B.Tech Computer Science Engineering Student

### Interests

- Full Stack Development
- Backend Engineering
- AI Applications
- Web3
- Cloud Computing
- System Design

### GitHub

https://github.com/asyncShaurya

### LinkedIn

linkedin.com/in/shaurya-singh-2811b432a/

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Your support motivates me to build and share more open-source projects.

---

# 📄 License

This project is licensed under the MIT License.
