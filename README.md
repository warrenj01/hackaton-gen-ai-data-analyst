****Credit Card Fraud Detection using Random Forest****

**What is this project?**

This project about developing a highly accurate machine learning model to detect fraudulent transactions in a public credit card dataset.
Particular attention should be given to minimize false positive.

**Problem Solved**

Credit card fraud detection is challenging due to extreme data imbalance (very few fraud cases). Our solution minimizes false alarms, ensuring operational efficiency for financial institutions.

**Key Features**
Feature Engineering Pipeline: Transforms raw Time and skewed Amount features into relevant inputs for the model.

Imbalance Handling: Uses the SMOTE (Oversampling) technique to balance the training data, allowing the model to effectively learn the rare fraud patterns.

High Performance: Achieves 86% Precision and 85% Recall on the fraud class, confirmed by an AUC score of 0.973.

Deployable Model: The trained Random Forest Classifier is saved as rf_fraud_model.pkl for immediate use in real-time scoring systems.

**How to Run the Project**
The entire analysis, modeling, and evaluation are conducted within the provided Jupyter Notebook (hackaton.ipynb).

**Prerequisites**

You need Python installed. All required packages can be installed via pip:

pip install pandas numpy scikit-learn imbalanced-learn matplotlib joblib

Option 1: Run Locally (Recommended)
Clone the Repository:

Start Jupyter:

Open the Notebook: Open the hackaton.ipynb file in your browser.

Execute Cells: Run all cells sequentially (e.g., using "Run All" or Shift+Enter) to reproduce the entire data analysis, training, and evaluation pipeline.

**Option 2: Run on Google Colab**
Upload Files: Upload the hackaton.ipynb file to your Google Drive. Ensure the dataset (if separate) and the saved model files (if analyzing the results) are also uploaded.

Open in Colab: Open the notebook in Google Colab.

Install Libraries: Run the first cell(s) to install all required libraries (e.g., !pip install imbalanced-learn).

Execute Cells: Run all cells in order to process the data and train the model.

