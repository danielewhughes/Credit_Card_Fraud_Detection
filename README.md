# Credit Card Fraud Detection (RandomForestClassifier)

This project develops a **machine learning model** to detect **fraudulent credit card transactions** using historical transaction data. The goal is to analyze behavioral and numerical transaction patterns to distinguish **normal** vs **fraudulent** activity using a **RandomForestClassifier**.

> **Notebook:** `fraud_detection.ipynb`

---

## Project Overview

Credit card fraud is a major challenge due to its **highly imbalanced nature** — fraudulent transactions represent only a tiny fraction of total activity.  
This project uses historical labeled transaction data to:

- Learn patterns that separate genuine and fraudulent transactions  
- Train a **RandomForestClassifier** to detect anomalies effectively  
- Evaluate classification performance using common fraud‑detection metrics  

---

## Requirements

This project uses common data‑science libraries:

- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`
- `jupyter`

---

## Getting Started

### 1) Clone the repo
``` bash
git clone https://github.com/danielewhughes/Credit_Card_Fraud_Detection.git
cd Credit_Card_Fraud_Detection
```

### 2) Create a virtual environment
``` bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
```

### 3) Install dependencies
``` bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 4) Open the notebook
``` bash
jupyter notebook fraud_detection.ipynb
```
