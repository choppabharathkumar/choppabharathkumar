# Hi, I'm Choppa Bharath Kumar

AI/ML and data engineering graduate building end-to-end data pipelines, explainable ML, and RAG applications in Python.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/choppabharathkumar/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:bharathchoppa005@gmail.com)

```python
class BharathKumar:
    role = "Computer Science & Engineering graduate"
    focus = ["AI/ML", "Data Engineering", "Applied GenAI"]
    languages = ["Python", "SQL"]
    building = ["ETL pipelines", "Explainable ML", "RAG applications"]
    looking_for = "AI/ML Engineer, Data Engineer, Data Scientist / Analyst roles"
    location = "Nellore, India"
```

**Start here:** [Hybrid Network Intrusion Detection System](https://github.com/choppabharathkumar/hybrid-ids-ml), my most complete project.

## About Me

Computer Science & Engineering graduate with dedicated AI/ML training and hands-on projects across the data-to-model lifecycle: data collection, SQL storage, validation, modeling, explainability, and retrieval-based GenAI. I'm looking for entry-level AI/ML, data engineering, and data science or analyst roles.

## Selected Projects

### Hybrid Network Intrusion Detection System

Detects known attack signatures and previously unseen anomalous traffic on CIC-IDS2017, and explains each alert.

**Stack:** Python, Pandas, NumPy, scikit-learn, Snort, SHAP, Streamlit, pytest

- Two-layer design: signature-based detection (Snort) plus an unsupervised Isolation Forest that catches anomalies static rules miss.
- Detection rates: **92.1% Port Scan, 87.8% Brute Force, 96.9% XSS**.
- SHAP explains each anomaly. A risk engine gives a 0–100 score with severity and remediation guidance.
- Streamlit dashboard and pytest test suite.

[Repository](https://github.com/choppabharathkumar/hybrid-ids-ml)

### End-to-End Data & AI Engineering Platform

One repository covering web data collection, SQL storage, ML analytics, and a RAG support assistant.

**Stack:** Python, BeautifulSoup, SQLite, Pandas, scikit-learn, ChromaDB, LangGraph, FastAPI

- **Data pipeline:** scraped book records across 3 categories into a two-table SQLite database (primary and foreign keys) and validated 6 SQL queries against equivalent `pandas.merge()` outputs in a Git-managed ETL pipeline.
- **Analytics:** Titanic classification pipeline (Logistic Regression, Decision Tree, Random Forest) with class-imbalance handling and GridSearchCV tuning: **82.02% accuracy, 75.76% F1, 0.8215 AUC**.
- **Support assistant:** RAG question answering using embeddings, ChromaDB semantic retrieval, LangGraph, and a FastAPI service.

[Repository](https://github.com/choppabharathkumar/zepto-data-ai-platform)

### TrendPulse

A Python ETL and analysis pipeline for live Hacker News stories.

**Stack:** Python, requests, Pandas, NumPy, Matplotlib

- Collects top stories from the Hacker News public API and saves them as JSON.
- Cleans the data (duplicates, missing values, low-quality entries) and writes CSV output.
- Derives engagement score and popularity flag, then charts top stories, category distribution, and score vs. comments.

[Repository](https://github.com/choppabharathkumar/trendpulse-bharath)

## Technical Stack

| Area | Tools |
|---|---|
| Languages & Databases | Python, SQL, MySQL, SQLite |
| Data & Analytics | Pandas, NumPy, Matplotlib, EDA, feature engineering |
| Data Engineering | BeautifulSoup web scraping, ETL pipelines, data cleaning and validation |
| Machine Learning | scikit-learn, classification, regression, Isolation Forest, GridSearchCV, SHAP |
| GenAI / AI Applications | RAG, embeddings, semantic retrieval, ChromaDB, LangGraph, FastAPI |
| Tools | Git, GitHub, Docker (basics), Linux, Streamlit, pytest |

## Background

- **Experience:** Python Programming Intern (1 month), YBI Foundation, January 2025
- **Education:** B.E. Computer Science and Engineering, R.M.D. Engineering College, Tamil Nadu (2022–2026)
- **Certification:** Artificial Intelligence and Machine Learning, Vishlesan I-Hub, IIT Patna
