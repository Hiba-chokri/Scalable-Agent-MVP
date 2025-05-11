# Scalable-Agent-MVP
ai-financial-agent/
# 🧠 AI Financial Market Agent

This project is an intelligent AI agent that monitors stock market trends, analyzes financial news, and estimates their impact on real estate prices using NLP and light data modeling.

## 🛠 Features
- Web-scrapes stock market + news headlines
- Summarizes financial news using GPT
- Correlates signals with housing market indicators
- Builds memory over time (tracks changing insights)
- Optional: Streamlit report viewer

## 💻 Stack
- Python, LangChain, OpenAI API, FAISS or ChromaDB
- yFinance, newspaper3k, Ray (optional)
- Streamlit (optional UI)

## 📦 Setup
```bash
pip install -r requirements.txt
python main.py

