# 🧠 ResumeIQ — AI Resume Analyzer

> Upload your resume + paste a job description → Get an AI-powered match score, skill gap analysis, and actionable improvements instantly.

![Made with Groq](https://img.shields.io/badge/AI-Groq%20%2B%20Llama%203-orange?style=for-the-badge)
![No Backend](https://img.shields.io/badge/Backend-None%20Required-6affcb?style=for-the-badge)
![Deployed on](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-7c6aff?style=for-the-badge)

---

## 🔴 Live Demo

👉 **[Try it here](https://YOUR_USERNAME.github.io/resumeiq)**

---

## ✨ Features

- 📄 **PDF Resume Upload** — Reads and extracts text from any resume PDF
- 💼 **Job Description Matching** — Paste any JD and get an instant compatibility score
- 🎯 **Match Score (0–100%)** — ATS-style scoring with animated ring chart
- ✅ **Matching Skills** — Skills you already have that the job wants
- ❌ **Missing Skills** — Gaps to fill before applying
- 💪 **Strengths** — What stands out about your resume
- 🔧 **Improvement Suggestions** — Specific, actionable changes to make
- 🤖 **ATS Tips** — How to pass automated screening systems

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Frontend | HTML, CSS, Vanilla JavaScript |
| AI Model | Llama 3.3 70B (via Groq API) |
| PDF Parsing | PDF.js (runs in browser) |
| Hosting | GitHub Pages |
| Backend | ❌ None — fully client-side |

---

## 🚀 How to Use

1. Open the [live app](https://YOUR_USERNAME.github.io/resumeiq)
2. Get a **free Groq API key** at [console.groq.com/keys](https://console.groq.com/keys)
3. Paste your key and click **Save**
4. Upload your **resume as a PDF**
5. Paste the **job description** you're applying for
6. Click **Analyze My Resume** and get results in seconds!

> 🔒 Your API key is stored only in your browser's localStorage — it is never sent to any server.

---

## 📁 Project Structure

```
resumeiq/
└── index.html    ← Entire app in one file (HTML + CSS + JS)
```

No dependencies to install. No build step. No server. Just one HTML file.

---

## 🔑 Getting a Free Groq API Key

1. Go to [console.groq.com](https://console.groq.com)
2. Sign up with your Google account (free, instant)
3. Click **API Keys** → **Create API Key**
4. Copy and paste it into the app

**Free tier:** 30 requests/day — more than enough for personal use.

---

## 🖥️ Run Locally

No installation needed! Just clone and open:

```bash
git clone https://github.com/YOUR_USERNAME/resumeiq.git
cd resumeiq
# Open index.html in your browser
```

Or serve it locally:

```bash
npx serve .
```

---

## 📝 Resume Bullet Point (for your own resume 😄)

> *Built and deployed a full-stack AI Resume Analyzer using Groq's Llama 3.3 API and PDF.js — analyzes resume-job fit with LLM, providing ATS match score, skill gap detection, and improvement suggestions. Deployed on GitHub Pages with zero backend.*

---

## 📸 Screenshot

![ResumeIQ Screenshot](screenshot.png)
> *(Add a screenshot of your app here for extra impact on GitHub)*

---

## 📄 License

MIT License — free to use, fork, and build on.

---

## 🙋 Author

Built by **YOUR_NAME** · [GitHub](https://github.com/YOUR_USERNAME) · [LinkedIn](https://linkedin.com/in/YOUR_PROFILE)
