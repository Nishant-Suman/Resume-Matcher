<div align="center">

[![Resume Matcher](assets/header.png)](https://www.resumematcher.fyi)

# Resume Matcher

Create tailored resumes for each job application with AI-powered suggestions. Works locally with Ollama or connect to your favorite LLM provider via API.

![Resume Matcher Demo](assets/Resume_Matcher_Demo_2.gif)

</div>

---

## 🚀 Features

* AI-powered resume parsing
* Resume-job matching & scoring
* Keyword highlighting
* Cover letter generation
* Multiple resume templates
* PDF export

---

## 🛠 Tech Stack

* Backend: FastAPI, Python
* Frontend: Next.js, React
* AI: OpenAI / Ollama
* Database: TinyDB

---

## ⚡ How It Works

1. Upload your resume
2. Paste job description
3. Get AI suggestions
4. Improve & export resume

---

## 📦 Installation

### Backend

```bash
cd apps/backend
cp .env.example .env
uv sync
uv run uvicorn app.main:app --reload --port 8000
```

### Frontend

```bash
cd apps/frontend
npm install
npm run dev
```

Open: http://localhost:3000

---

## 🔑 Configuration

Edit `.env`:

```env
LLM_PROVIDER=openai
LLM_API_KEY=your_api_key_here
```

OR use local AI:

```env
LLM_PROVIDER=ollama
LLM_MODEL=gemma3:4b
LLM_API_BASE=http://localhost:11434
```

---

## 🎯 Use Cases

* Resume screening
* Job matching
* Resume optimization

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
