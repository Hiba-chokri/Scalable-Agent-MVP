# Scalable-Agent-MVP
ai-financial-agent/
│
├── README.md
├── requirements.txt
├── main.py                   # Main agent loop
├── agent/
│   ├── __init__.py
│   ├── planner.py           # Task planning logic
│   ├── memory.py            # Memory system (Chroma/FAISS or flat)
│   ├── tools.py             # Scrapers, APIs, utils
│   ├── analyzer.py          # Core logic for correlation (stocks ↔ housing)
│   └── nlp.py               # LLM calls + news summarization
│
├── data/
│   ├── raw/                 # Raw scraped data
│   ├── processed/           # Cleaned + parsed
│   └── memory.json          # Memory file if local
│
├── notebooks/
│   └── experiment.ipynb     # For trying models or correlation formulas
│
└── streamlit_app.py         # Optional UI to display reports
