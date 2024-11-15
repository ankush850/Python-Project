# COVID-19 Statewise Vaccination & Time Series Analysis

## 📌 Project Overview
This project performs an extensive data analytics lab study focusing on **COVID-19 state-wise vaccination progression**, epidemiological trends, demographic distributions, and **Time Series Forecasting / Regression Analysis**.

---

## 🔬 Core Components & Analysis
1. **Data Preprocessing & Cleaning**:
   - Handling null values, date parsing, cumulative metric conversions, and state-level aggregations.
2. **Descriptive & Exploratory Analysis**:
   - First Dose vs. Second Dose completion rates across Indian states.
   - Male vs. Female vaccination distribution and youth vs. senior coverage.
   - Covaxin vs. Covishield dose proportions over time.
3. **Time Series & Predictive Modeling**:
   - Seasonal trend decomposition and moving average smoothing.
   - Regression and forecasting models evaluated using Scikit-learn and Statsmodels.
   - Model persistence and metric checkpoints using `joblib`.

---

## 📦 Requirements & Installation
Install dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `pandas` - Time series indexing and state aggregations
- `numpy` - Vectorized calculations
- `matplotlib` & `seaborn` - Time series plots, bar charts, and dose progressions
- `statsmodels` - Time series decomposition and statistical models
- `scikit-learn` - Regression metrics and forecasting models
- `joblib` - Model serialization and persistence
- `jupyter` / `notebook` - Notebook runtime

---

## 🚀 How to Run
Open and run the notebook:

```bash
jupyter notebook miniprojectdsbdal31232.ipynb
```
