# Waste Segregation & Classification Machine Learning Model

<p align="center">
<a href="https://github.com/ankush850"><img src="https://img.shields.io/static/v1?logo=github&label=maintainer&message=ankush850&color=blue" alt="Maintainer"/></a>
<a href="https://github.com/ankush850/Data-Analyst-Mini-Projects"><img src="https://img.shields.io/badge/Status-Complete-brightgreen" alt="Status"/></a>
</p>

## 📌 Project Overview
A machine learning classification project that models automated **waste segregation** into recyclable, organic, hazardous, and general trash categories based on physical attributes and sensor features.

---

## 🔬 Workflow & Architecture
1. **Data Ingestion & Encoding**: Loads dataset attributes and performs `LabelEncoder` transformations on target waste classes.
2. **Feature Preprocessing & Train-Test Split**: Divides dataset using stratified `train_test_split`.
3. **Deep Learning Model**: Constructs a multi-layer Neural Network with `TensorFlow / Keras` featuring Dense layers, Dropout regularization, and Softmax classification.
4. **Evaluation & Metrics**: Computes confusion matrix, precision, recall, and classification accuracy curves using `seaborn` and `matplotlib`.

---

## 📦 Requirements & Installation
Install dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies
- `tensorflow` - Neural network architecture and training
- `scikit-learn` - Data splitting, label encoding, and metrics
- `pandas` - Dataset manipulation
- `seaborn` & `matplotlib` - Loss curves and confusion matrices
- `jupyter` - Interactive notebook environment

---

## 🚀 How to Run
Open and run the notebook:

```bash
jupyter notebook Untitled10.ipynb
```
