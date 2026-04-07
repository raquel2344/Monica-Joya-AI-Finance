# Monica Joya — AI in Finance
### ITAI 3378 | Houston City College | Spring 2026

This repository contains all coursework, projects, and certifications completed as part of the AI in Finance course in the Bachelor of Applied Technology in Artificial Intelligence & Robotics program.

---

## 🏆 Capstone Project — InvestorInsight AI

> A RAG-powered web application that reads any public company's 10-K filing from SEC EDGAR and transforms it into an interactive investor experience — live, free, and accessible from any device.

**Live app:** [https://huggingface.co/spaces/raquel2344/InvestorInsightAI](https://huggingface.co/spaces/raquel2344/InvestorInsightAI)

### What it does
- 📊 Generates an interactive Sankey chart showing how money flows through the business
- 💡 Produces a plain-English financial story and bucket breakdown with LLM reasoning
- 📄 Downloads a comprehensive ~2,500 word investor report as a PDF
- 💬 Answers questions via a RAG chatbot grounded in the actual 10-K filing

### Tech Stack

| Layer | Technology |
|-------|-----------|
| Data Ingestion | SEC EDGAR API |
| Text Processing | RecursiveCharacterTextSplitter + BeautifulSoup |
| Embeddings | HuggingFace all-MiniLM-L6-v2 |
| Vector Store | FAISS |
| LLM | Groq llama-3.3-70b-versatile |
| RAG | Decoupled retrieval + direct LLM call |
| UI | Gradio 5 |

**Team:** Monica (Raquel) Joya · Andrew Badzioch · Trevon Woods

---

## 📂 Repository Structure

```
Monica-Joya-AI-Finance/
├── Team Capstone Project/
│   └── InvestorInsightAi/   ← Capstone project (live on HuggingFace)
├── assignments/             ← Course assignments (coming soon)
├── certificates/            ← Course certifications (coming soon)
└── README.md                ← You are here
```

---

## About

Monica Joya is a student at Houston City College pursuing a Bachelor of Applied Technology in Artificial Intelligence & Robotics. She has a background in Oil and Gas and algorithmic trading.

**GitHub:** [github.com/raquel2344](https://github.com/raquel2344)
