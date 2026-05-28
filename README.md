# Kole Robertson — Data Project Portfolio

A curated index of my data and machine learning projects. Strongest work is at the top.

For a shorter, recruiter-friendly view of the highlights, see my [GitHub profile page](https://github.com/kdr47101).

## Contents

- [Competitions](#competitions)
- [Data Analytics & SQL](#data-analytics--sql)
- [Machine Learning & Modeling](#machine-learning--modeling)
- [Data Engineering & Pipelines](#data-engineering--pipelines)
- [Learning Notes & Other](#learning-notes--other)

---

## Competitions

| Project | Result | Tools | Description |
| --- | --- | --- | --- |
| **[CAFA 6 — Protein Function Prediction](https://github.com/kdr47101/cafa-6-protein-function-prediction)** | **7th of 2,256** (top 0.3%, provisional) | Python, PyBoost (GPU gradient boosting), PyTorch, RAPIDS | International protein-function prediction competition: extreme multi-label classification across thousands of Gene Ontology terms. Built on a strong prior-year baseline with custom function encoding, tuned PyBoost parameters, and a refined GO-hierarchy strategy combining propagated and non-propagated models. |
| **[Omnilex — Agentic Legal Information Retrieval](https://github.com/kdr47101/omnilex-agentic-legal-retrieval)** | **Top 12%** | Python, Qwen3 embeddings, vLLM, self-hosted Qwen3-32B, llama-cpp-python | Multi-stage retrieval pipeline over a ~2M-document multilingual Swiss legal corpus. Combined regex citation extraction, dense embeddings, citation-fingerprint filtering, HyDE query generation via a self-hosted LLM, and LLM-based pointwise reranking. |
| **[UTSC SDG Data Challenge](https://github.com/kdr47101/UTSC-SDG-Data-Challenge)** | **1st Place, "Best in Show"** | Python (NumPy, pandas, seaborn, matplotlib), Power BI | Top overall prize for analysis and presentation quality. Tested whether countries can grow real GDP per capita (SDG 8.1.1) while holding or reducing GHG emissions (SDG 13.2.2) using 24 years of World Bank data. Built a β-ratio and multiple regression model explaining ~50% of variance via industry share, resource rents, and FDI. |
| [IMI Big Data and AI Competition Submission](https://github.com/kdr47101/IMI-Big-Data-and-AI-comp-submission) | — | Python (pandas, scikit-learn, TensorFlow), Jupyter, Docker, Bash | End-to-end AML transaction analytics pipeline: cleans multi-source bank data, runs IsolationForest anomaly detection, logs results, and exports per-channel anomalies and visualizations for downstream review. |
| [Loan Payback Prediction (Kaggle)](https://github.com/kdr47101/Kaggle-Competition-Predicting-Loan-Payback) | — | Python (pandas, NumPy, scikit-learn, XGBoost, LightGBM, Optuna), Jupyter | Kaggle competition predicting loan repayment probability with LightGBM. Applied target encoding with smoothing for high-cardinality features and label encoding elsewhere. Optimized hyperparameters with Optuna across 200 trials with 10-fold stratified cross-validation. |

---

## Data Analytics & SQL

| Project | Tools | Description |
| --- | --- | --- |
| [Toronto Consulting Services Expenditures Analysis](https://github.com/kdr47101/Toronto-Consulting-Services-Expenditures-Analysis) | Python | Analysis of City of Toronto consulting spend using open civic data — cleaning, exploration, and visualization to surface patterns in how public funds are allocated across departments and vendors. |
| [Supply Chain Optimization](https://github.com/kdr47101/Supply-Chain-Optimization) | Python (pandas, NumPy), Jupyter, Power BI | End-to-end analysis of logistics data to optimize shipment efficiency and improve supply-chain visibility. Includes cleaning and exploring the dataset, plus a Power BI dashboard highlighting top routes, delay drivers, supplier performance trends, and peak shipment periods. |
| [8-Week SQL Challenge](https://github.com/kdr47101/8-Week-SQL-Challenge) | SQL | Solutions to the eight case studies from the [8 Week SQL Challenge](https://8weeksqlchallenge.com/) — joins, aggregations, window functions, and query design across realistic business scenarios. |

---

## Machine Learning & Modeling

| Project | Tools | Description |
| --- | --- | --- |
| [Complaint-Driven Product Idea Miner](https://github.com/kdr47101/Complaint-Driven-Product-Idea-Miner) | Python, Streamlit, Reddit API (PRAW), Google Gemini API, MongoDB Atlas | End-to-end Streamlit application that mines Reddit for user complaints and extracts product opportunities. Uses Gemini to identify relevant subreddits and surface actionable ideas with AI-scored relevance, with customizable search parameters, ranked results, and CSV export. |

---

## Data Engineering & Pipelines

| Project | Tools | Description |
| --- | --- | --- |
| [Uber Data Engineering Project](https://github.com/kdr47101/Uber-Data-Engineering-Project) | Python, GCP (Cloud Storage, Compute Engine, BigQuery), Mage, Looker Studio | End-to-end ETL pipeline for NYC trip-record data: extraction from raw sources, Python transformation, fact-and-dimensional modeling, Mage orchestration, and a Looker Studio dashboard. |

---

## Learning Notes & Other

| Project | Tools | Description |
| --- | --- | --- |
| [ISLP — Personal Solutions](https://github.com/kdr47101/ISLP-Personal-Solutions) | Python (NumPy, pandas, scikit-learn, statsmodels, matplotlib), Jupyter | Personal, reproducible solutions to *An Introduction to Statistical Learning with Python* labs and exercises: regression, classification, resampling, regularization, non-linear models, trees, SVM, and unsupervised learning. |
