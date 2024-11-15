# TMDb Movie Dataset: Exploratory Data Analysis & Investigation

## 📌 Project Overview
This project performs an extensive exploratory data analysis on a dataset containing information on over **10,000 movies** collected from The Movie Database (TMDb).

The analysis investigates patterns, correlations, and business questions surrounding movie success, budgets, revenues, runtimes, genres, and release timing over several decades.

---

## 🔍 Key Research Questions
1. **Financial Success**: Which movie generated the highest net profit, and which experienced the biggest financial loss?
2. **Budget vs. Revenue**: How strongly does production budget correlate with box office revenue?
3. **Genre Popularity & Profitability**: Which film genres are produced most frequently, and which genres yield the highest average profit?
4. **Runtime Trends**: What is the ideal movie duration associated with higher ratings and viewer popularity?
5. **Trends Over Time**: How have movie release volumes and average revenues evolved across decades?

---

## 📊 Dataset Information
- **`tmdb-movies.csv`**: Raw dataset containing movie metadata (popularity, budget, revenue, runtime, vote count, vote average, genres, release year).
- **`clean_df_tmdb.csv`**: Cleaned dataset after removing zero-revenue/budget entries, handling missing values, standardizing dates, and engineering profit metrics.

---

## 💡 Key Insights
- **Budget & Revenue Correlation**: A strong positive correlation exists between production budget and gross revenue. High-budget films are disproportionately represented among the highest-grossing titles.
- **Top Genres**: Drama and Comedy are the most common genres by count, but Adventure, Sci-Fi, and Animation generate significantly higher average worldwide revenues.
- **Optimal Runtime**: The vast majority of top-rated movies fall within the 100–130 minute window.
- **Release Timing**: Movies released during summer (May–July) and the holiday season (November–December) exhibit peak revenue trends.

---

## 📦 Requirements & Installation
Install dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `pandas` - Data cleaning, aggregation, and profit calculation
- `numpy` - Numerical statistics
- `matplotlib` & `seaborn` - Distribution plots, scatter plots, and bar charts
- `jupyter` / `notebook` - Interactive notebook execution

---

## 🚀 How to Run
Run the Jupyter Notebook:

```bash
jupyter notebook Harsh-Deep-Kalita-TMDb-Data-Set.ipynb
```
Or open the static HTML export:
- `Harsh-Deep-Kalita-TMDb-Data-Set.html`
