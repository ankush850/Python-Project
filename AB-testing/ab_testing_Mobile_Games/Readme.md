# Cookie Cats: Mobile Game A/B Testing & Player Retention

## 📌 Project Overview
*Cookie Cats* is a popular mobile puzzle game developed by Tactile Entertainment. As players progress through the levels, they encounter gates that force them to wait or make an in-app purchase before continuing.

In this project, we analyze an A/B test where the first gate was moved from **Level 30 (`gate_30` - control group)** to **Level 40 (`gate_40` - test group)** to evaluate its impact on player retention.

---

## 📊 Dataset Description
The dataset `cookie_cats.csv` contains data for **90,189 players** who installed the game while the A/B test was running:

| Variable | Type | Description |
| :--- | :--- | :--- |
| `userid` | Integer | Unique identification number for each player |
| `version` | String | Control group (`gate_30`) or test group (`gate_40`) |
| `sum_gamerounds` | Integer | Number of game rounds played by the player during the first 14 days after install |
| `retention_1` | Boolean | Did the player return and play 1 day after installing? |
| `retention_7` | Boolean | Did the player return and play 7 days after installing? |

---

## 🔬 Methodology & Key Findings
1. **1-Day Retention**:
   - `gate_30`: 44.82%
   - `gate_40`: 44.23%
   - Bootstrapping reveals a **96.0% probability** that 1-day retention is higher when the gate is at Level 30.
2. **7-Day Retention**:
   - `gate_30`: 19.02%
   - `gate_40`: 18.20%
   - Bootstrapping indicates a **99.8% probability** that 7-day retention is higher when the gate is placed at Level 30.
3. **Statistical Significance**:
   - Chi-Square test of independence confirms a statistically significant drop in 7-day retention when the gate is moved to Level 40 ($p < 0.05$).
4. **Recommendation**:
   - **Keep the gate at Level 30** to maximize long-term player retention and engagement.

---

## 📦 Requirements & Installation
Install the project dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `pandas` - Data manipulation and grouping
- `numpy` - Numerical computing & bootstrap sampling
- `scipy` - Statistical tests (Chi-Square, normality)
- `statsmodels` - Statistical models and distributions
- `matplotlib` & `seaborn` - Distribution & retention visualizations
- `jupyter` / `notebook` - Interactive notebook execution

---

## 🚀 How to Run
Launch the Jupyter Notebook:

```bash
jupyter notebook AB_Testing_Cookies_Dataset.ipynb
```
