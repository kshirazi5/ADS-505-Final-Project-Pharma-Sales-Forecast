# ADS-505 Final Project: Predictive Modeling for Pharmaceutical Sales Performance

## 📖 Project Purpose
This project uses **historical pharmaceutical sales data** to build predictive models that forecast future demand. Accurate forecasting can help optimize inventory, reduce waste, and guide production strategies. By analyzing multi-year sales patterns, we aim to show how data science can provide **real-world value** in the pharmaceutical industry.

---

## 📦 Dataset
- **Source:** [Pharma Sales Data — Kaggle (Milan Zdravković)](https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data?resource=download)  
- **Size:** ~600,000 transaction records (2014–2019)  
- **Variables:** Date/time of sale, drug brand (57 brands), ATC category (8 categories), quantity sold  
- **Format:** Multiple CSVs; can be aggregated hourly/weekly for analysis  
- **Use Case:** Commonly used for time-series forecasting and trend analysis

---

## 🎯 Objectives
- Explore multi-year sales data across therapeutic categories  
- Identify key drivers of demand and seasonality  
- Compare modeling approaches: **SARIMA**, **XGBoost**, **Random Forest**, **Linear Regression** (and optional **LSTM**)  
- Translate results into **business recommendations** for demand planning and inventory optimization

---

## 🌿 Branch Workflow
- `main` → stable, protected branch  
- `kiara`, `saloni`, `kamran` → feature branches; merge into `main` via Pull Requests

---

## 👥 Team Contributions
- **Saloni Barhate** → Data preprocessing/cleaning, EDA, **XGBoost**, paper & presentation  
- **Kamran Shirazi** → Feature engineering, **Random Forest**, forecasting, paper & presentation  
- **Kiara Paz** → Visualization & dashboards, **Linear Regression**, paper & presentation

---

## 🗂️ Repo Structure
data/ # raw, interim, processed (ignored)
notebooks/ # exploratory notebooks
src/ # scripts and models
reports/ # figures, tables, write-ups
README.md # project overview

