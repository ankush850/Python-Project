# Analyze A/B Test Results: E-Commerce Landing Page Conversion

## 📌 Project Overview
An e-commerce website performed an A/B test to decide whether they should implement a new landing page (`treatment`) or stick with the old landing page (`control`).

The goal of this project is to guide company decision-makers through statistical analysis:
1. **Probability Analysis**: Baseline conversion rates and initial discrepancies.
2. **Hypothesis Testing**: Sampling distribution under the null hypothesis ($H_0: p_{new} \le p_{old}$) vs alternative hypothesis ($H_1: p_{new} > p_{old}$) and Z-test evaluation.
3. **Logistic Regression Modeling**: Fitting logistic regression models with categorical dummy variables and interaction terms across geographic locations (US, UK, CA).

---

## 📊 Datasets
- **`ab_data.csv`**: Contains 294,478 rows tracking user sessions, assigned group (`control` vs `treatment`), landing page (`old_page` vs `new_page`), and conversion status (`0` or `1`).
- **`countries.csv`**: Maps `user_id` to user country of origin (`US`, `UK`, `CA`).

---

## 🔬 Statistical Findings & Conclusions
- **P-Value & Hypothesis Test**: Under the null hypothesis simulation, the calculated $p$-value was $\approx 0.90$, failing to reject the null hypothesis at $\alpha = 0.05$.
- **Z-Score Test**: $Z$-score was approximately $-1.31$, confirming the result.
- **Logistic Regression**: The page coefficient has a $p$-value $> 0.05$, indicating that the new page does not have a statistically significant effect on conversion rate compared to the old page.
- **Geographic Impact**: Adding country dummy variables and their interactions with the landing page did not yield statistically significant predictive power.
- **Business Recommendation**: **Retain the old landing page**, as the new page demonstrates no statistically significant increase in conversions to justify development and migration costs.

---

## 📦 Requirements & Installation
Install the project dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `pandas` - Data cleaning and dataset merging
- `numpy` - Sampling distributions & simulations
- `scipy` - Normal distributions & Z-score evaluation
- `statsmodels` - Logistic regression modeling (`Logit`)
- `matplotlib` - Distribution histograms & visualization
- `jupyter` / `notebook` - Notebook runtime environment

---

## 🚀 How to Run
Launch the notebook:

```bash
jupyter notebook Analyze_ab_test_results_notebook.ipynb
```
