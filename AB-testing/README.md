# A/B Testing Projects

This directory contains two comprehensive statistical A/B testing projects analyzing user retention and e-commerce conversion rates.

---

## 📁 Projects in this Directory

### 1. [Mobile Games A/B Testing (`ab_testing_Mobile_Games`)](file:///d:/Data-Analyst-Mini-Projects-main/AB-testing/ab_testing_Mobile_Games/README.md)
- **Problem**: Analyze the impact of moving the first progression gate in the mobile puzzle game *Cookie Cats* from Level 30 to Level 40.
- **Key Techniques**: Bootstrapping distributions, 1-day & 7-day retention analysis, Chi-Square test of independence, KDE density estimation.
- **Dataset**: `cookie_cats.csv` (90,189 players).

### 2. [Analyze A/B Test Results (`analyze-ab-test-results`)](file:///d:/Data-Analyst-Mini-Projects-main/AB-testing/analyze-ab-test-results/README.md)
- **Problem**: Help an e-commerce website decide whether to roll out a new landing page design or keep the old one based on conversion rate data.
- **Key Techniques**: Probability analysis, hypothesis testing with sampling distributions, Z-score test, Logistic Regression with interaction terms (country variables).
- **Datasets**: `ab_data.csv` (294,478 entries), `countries.csv`.

---

## 🛠️ Environment Setup

Each subproject has its own `requirements.txt`. To run any project, navigate into its folder:

```bash
cd ab_testing_Mobile_Games
# OR
cd analyze-ab-test-results

pip install -r requirements.txt
jupyter notebook
```
