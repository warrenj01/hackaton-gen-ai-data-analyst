# Credit Card Fraud Detection (Hackathon Project)

## Overview

This project demonstrates a machine learning solution for detecting fraudulent credit card transactions using a public, highly imbalanced dataset. The goal is to help financial institutions reduce false alarms while effectively identifying fraud.

## Problem Statement

Credit card fraud is rare but costly. Detecting it is challenging due to class imbalance—fraudulent transactions are much less frequent than genuine ones. This project uses data science techniques to build and evaluate effective fraud detection models.

## Main Steps

- **Exploratory Data Analysis (EDA):** Understands data distribution and class imbalance.
- **Feature Engineering:** Creates new features (like log-transformed Amount or transaction Hour) to help the model learn better patterns.
- **Imbalance Handling:** Uses SMOTE to oversample the minority (fraud) class during training.
- **Modeling:** Trains and evaluates both a Random Forest classifier and a Logistic Regression model.
- **Evaluation:** Reports results using metrics like precision, recall, and ROC-AUC, focusing on minimizing false positives.

## Getting Started

### Prerequisites

- Python 3.8+ recommended.
- Install requirements:
  ```bash
  pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn joblib
  ```

### Running the Notebook

1. **Clone the repository:**
   ```bash
   git clone https://github.com/warrenj01/hackaton-gen-ai-data-analyst.git
   cd hackaton-gen-ai-data-analyst
   ```
2. **Start Jupyter:**
   ```bash
   jupyter notebook
   ```
3. **Open and Run the Notebook:** Open `hackaton.ipynb` and run the cells in sequence.

*Alternatively, upload the notebook to Google Colab and run all cells there. Make sure to also upload the dataset.*

## Files

- `hackaton.ipynb` — Main notebook with all analysis and modeling steps.
- `creditcard.csv` — Dataset (not included in repo; download from Kaggle).
- `rf_fraud_model.pkl` — Saved Random Forest model (created after running the notebook).
- `lr_fraud_model.pkl` — Saved Logistic Regression model (created after running the notebook).

## References

- [Original Dataset (Kaggle)](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

**Contact:** [warrenj01](https://github.com/warrenj01)
