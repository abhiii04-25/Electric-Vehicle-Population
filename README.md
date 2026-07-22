# Electric-Vehicle-Population
Exploratory Data Analysis (EDA) &amp; Machine Learning Project
# 🔋 Electric Vehicle Population — Exploratory Data Analysis & ML

A portfolio-worthy end-to-end analysis of a real-world Electric Vehicle (EV) registration dataset — covering data cleaning, exploratory data analysis, visualization, feature engineering, and machine learning preparation.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-150458)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4c72b0)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

---

## 📌 Project Overview

This project explores a dataset of registered electric vehicles to uncover patterns in manufacturer popularity, model trends, electric range, geographic adoption, and regulatory eligibility (CAFV). It's structured as a progressive skill-building exercise — starting with basic Pandas operations and ending with machine learning-ready features — making it a strong showcase piece for data analyst / data scientist roles.

## 🗂️ Dataset

| Detail | Value |
|---|---|
| Rows | 279,780 |
| Columns | 16 |
| Key fields | `Make`, `Model`, `Model Year`, `Electric Vehicle Type`, `Electric Range`, `County`, `City`, `CAFV Eligibility`, `Electric Utility` |

> Add your dataset source link here (e.g. Kaggle / data.gov) and a short note on licensing.

## 🎯 Objectives

- Clean and prepare raw EV registration data for analysis
- Explore trends across manufacturers, models, geography, and time
- Visualize distributions and relationships using Matplotlib & Seaborn
- Engineer features (age category, range category, market share) for downstream ML
- Answer business-style questions relevant to EV market strategy
- Prepare the dataset for predictive modeling (range, vehicle type, CAFV eligibility)

## 🧰 Tech Stack

- **Python** — Pandas, NumPy
- **Visualization** — Matplotlib, Seaborn
- **Machine Learning (later stage)** — scikit-learn
- **Environment** — Jupyter Notebook

## 📁 Repository Structure

```
├── data/
│   └── ev_population.csv          # raw dataset (or link if too large for repo)
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_visualizations.ipynb
│   ├── 04_feature_engineering.ipynb
│   └── 05_ml_preparation.ipynb
├── images/
│   └── *.png                      # exported charts for README/portfolio use
├── requirements.txt
└── README.md
```

## 🔍 Analysis Roadmap

1. **Data Cleaning** — missing values, duplicates, column renaming, category typing, outlier detection
2. **Beginner EDA** — shape, dtypes, summary stats, unique counts, top manufacturers/models
3. **Intermediate EDA** — top 10 manufacturers/models, registrations by year, BEV vs PHEV split
4. **Advanced Visualization** — range distributions, boxplots, violin plots, correlation heatmap, pairplots
5. **Business Questions** — market leaders, fastest-adopting counties, Tesla expansion targets, CAFV trends
6. **Feature Engineering** — age category, range category, manufacturer ranking, market share
7. **Machine Learning Prep** — regression (range), classification (vehicle type / CAFV eligibility), clustering, anomaly detection

## 📊 Key Visualizations

- EV registrations over the years
- Top 15 manufacturers & top 15 cities by EV population
- Electric range distribution (histogram + KDE)
- BEV vs PHEV comparison
- Average range by manufacturer
- CAFV eligibility breakdown
- Correlation heatmap of numeric features
- Outlier boxplots for electric range

*(Add generated chart images here once notebooks are run, e.g. `![Top Manufacturers](images/top_manufacturers.png)`)*

## 💡 Key Insights

> Fill this in after completing the analysis — 4–6 bullet points summarizing the most interesting findings, e.g. market leader, fastest-growing county, average range trends by year, etc.

- Insight 1
- Insight 2
- Insight 3

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/<your-username>/ev-population-eda.git
cd ev-population-eda

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

## 📦 requirements.txt (suggested)

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

## 🔮 Future Work

- Build predictive models for electric range and CAFV eligibility
- Add an interactive dashboard (Plotly Dash / Streamlit)
- Deploy insights as a shareable web app

## 🙌 Acknowledgements

- Dataset source: *add link*
- Inspired by common data analyst / data scientist interview-style EDA challenges

⭐ If you found this project useful, consider starring the repo!
