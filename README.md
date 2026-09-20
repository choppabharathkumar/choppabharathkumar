<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f172a,100:1e3a8a&height=120&text=Choppa%20Bharath%20Kumar&fontColor=ffffff&fontSize=32&desc=AI%2FML%20%7C%20Data%20Engineering%20%7C%20Applied%20GenAI&descSize=16&descAlignY=72" alt="Choppa Bharath Kumar: AI/ML, Data Engineering, Applied GenAI" width="100%"/>

# Hi, I'm Choppa Bharath Kumar 👋

AI/ML and data engineering graduate building end-to-end data pipelines, explainable ML, and RAG applications in Python.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/choppabharathkumar/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:bharathchoppa005@gmail.com)

**Start here:** [Hybrid Network Intrusion Detection System](https://github.com/choppabharathkumar/hybrid-ids-ml), my most complete project.

## About Me

Computer Science & Engineering graduate with dedicated AI/ML training and hands-on projects across the data-to-model lifecycle: data collection, SQL storage, validation, modeling, explainability, and retrieval-based GenAI.

- Looking for: entry-level AI/ML, data engineering, and data science or analyst roles
- Ask me about: Python, SQL, ETL pipelines, scikit-learn, RAG, explainable ML
- Based in: Nellore, India

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

Also: ETL, web scraping (BeautifulSoup), EDA, feature engineering, Isolation Forest, GridSearchCV, SHAP, RAG, embeddings, ChromaDB, LangGraph, pytest, Matplotlib.

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

## Background

- **Experience:** Python Programming Intern (1 month), YBI
