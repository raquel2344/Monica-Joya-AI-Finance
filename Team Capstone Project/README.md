# 🏆 Team Capstone Project
### ITAI 3378 — AI in Finance | Houston City College | Group 1 | Spring 2026
**Team:** Monica (Raquel) Joya · Andrew Badzioch · Trevon Woods

---

## InvestorInsight AI

A RAG-powered web application that reads any public company's 10-K annual filing from SEC EDGAR and transforms it into an interactive investor experience — live, free, and accessible from any device.

**🌐 Live App:** [https://huggingface.co/spaces/raquel2344/InvestorInsightAI](https://huggingface.co/spaces/raquel2344/InvestorInsightAI)

---

## What It Does

Enter any stock ticker — V, AAPL, NVDA — and the app instantly generates:

- 📊 An interactive Sankey chart showing how money flows through the business
- 💡 A plain-English financial story with LLM reasoning behind each bucket
- 📄 A downloadable comprehensive investor report (~2,500 words, PDF)
- 💬 A RAG chatbot grounded in the company's actual 10-K filing

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Data Ingestion | SEC EDGAR API — live fetch, no auth required |
| Text Processing | RecursiveCharacterTextSplitter + BeautifulSoup |
| Embeddings | HuggingFace all-MiniLM-L6-v2 |
| Vector Store | FAISS |
| LLM | Groq llama-3.3-70b-versatile |
| RAG | Decoupled retrieval + direct LLM call |
| UI | Gradio 5 |

---

## Run It Locally

```bash
git clone https://github.com/raquel2344/Monica-Joya-AI-Finance
cd "Monica-Joya-AI-Finance/Team Capstone Project/InvestorInsightAi"
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
export GROQ_API_KEY=your_groq_key_here
python app.py
```


