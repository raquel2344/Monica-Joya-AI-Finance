# Monica Joya — AI in Finance
### ITAI 3378 | Houston City College | Spring 2026

This repository contains all coursework, projects, and certifications completed as part of the AI in Finance course in the Bachelor of Applied Technology in Artificial Intelligence & Robotics program.

---

## Projects

### InvestorInsightAI
A RAG-powered web application that analyzes any public company's 10-K annual filing from SEC EDGAR and generates an interactive Sankey chart, investor summary, downloadable PDF report, and Q&A chatbot.

- **Live app:** https://huggingface.co/spaces/raquel2344/InvestorInsightAI
- **Tech stack:** Python, LangChain, FAISS, Groq (Llama 3.3 70B), Gradio 5, SEC EDGAR API
- **Team:** Monica (Raquel) Joya, Andrew Badzioch, Trevon Woods

---

## Tech Stack Overview

| Layer | Technology |
|-------|-----------|
| Data Ingestion | SEC EDGAR API |
| Text Processing | RecursiveCharacterTextSplitter |
| Embeddings | HuggingFace all-MiniLM-L6-v2 |
| Vector Store | FAISS |
| LLM | Groq llama-3.3-70b-versatile |
| RAG | Decoupled retrieval + direct LLM call |
| UI | Gradio 5 |

---

## About

Monica Joya is a student at Houston City College pursuing a Bachelor of Applied Technology in Artificial Intelligence & Robotics. She has a background in Oil and Gas and algorithmic trading.

**GitHub:** github.com/raquel2344
