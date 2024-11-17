# WeRateDogs: Twitter Archive Data Wrangling & Analysis

## 📌 Project Overview
Real-world data rarely comes clean. In this project, data from the popular Twitter account **@dog_rates** (known as **WeRateDogs**) is gathered from multiple disparate sources, assessed for quality and tidiness issues, programmatically cleaned, and stored in a consolidated master dataset for analysis and visualization.

WeRateDogs is famous for rating dogs with humorous commentary, almost always giving ratings with numerators greater than 10 (e.g., 11/10, 12/10, 13/10).

---

## 🔄 Data Wrangling Pipeline

### 1. Data Gathering
- **Enhanced Twitter Archive (`twitter-archive-enhanced.csv`)**: Provided archive containing basic tweet metadata for 5,000+ tweets.
- **Image Predictions (`image-predictions.tsv`)**: Downloaded programmatically via `requests` library containing neural network predictions of dog breeds.
- **Tweet JSON Data (`tweet_json.txt`)**: Tweet engagement metrics (retweet count, favorite count) gathered via Twitter API / JSON lines archive.

### 2. Data Assessment
- **Quality Issues Identified & Resolved**:
  - Missing values in dog stages (`doggo`, `floofer`, `pupper`, `puppo`).
  - Incorrect data types (`tweet_id` formatted as integer instead of string, `timestamp` formatted as string instead of datetime).
  - Invalid dog names extracted from text (e.g., `'a'`, `'the'`, `'None'`).
  - Retweets and replies removed to focus strictly on original tweets with ratings.
  - Erroneous ratings extracted by regex (e.g., rating decimal fractions).
- **Tidiness Issues Identified & Resolved**:
  - Four separate dog stage columns combined into a single unified `dog_stage` variable.
  - Three distinct data tables merged on `tweet_id` into a clean master DataFrame.

### 3. Storing
- Cleaned dataset exported to `twitter_archive_master.csv`.

### 4. Visualizations & Insights
- High correlation observed between retweet counts and favorite counts.
- Puppers are the most frequently posted dog stage, while Puppos received the highest median rating.
- The most common predicted dog breeds include Golden Retriever, Labrador Retriever, and Pembroke Welsh Corgi.

---

## 📦 Requirements & Installation
Install dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `pandas` - Data wrangling, joining, and cleaning
- `numpy` - Numerical array operations
- `requests` - Programmatic HTTP data downloading
- `matplotlib` & `seaborn` - Visualizations and report charts
- `ipython` & `jupyter` - Interactive notebook execution

---

## 🚀 How to Run
Open and run the wrangling notebook:

```bash
jupyter notebook wrangle_act.ipynb
```
You can also view the exported reports:
- `wrangle_report.html` - Summary of wrangling efforts.
- `act_report.html` - Insights, visualizations, and conclusions.
