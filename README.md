# Credit Card Fraud Detection Analysis

## 📌 Project Context
It is essential for credit card companies to recognize fraudulent transactions so that customers are not charged for items they did not purchase. This project analyzes a dataset of transactions made by European cardholders in September 2013.

## 📊 Dataset Information
Due to its large size (~143MB), the raw data file is not hosted in this repository. 
* **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* **Stats:** 284,807 transactions with 492 frauds (0.172% of the total).
* **Features:** Contains 'Time', 'Amount', 'Class', and 28 PCA-transformed variables (V1-V28).

## 💻 What the Code Does
This project provides a complete Exploratory Data Analysis (EDA) pipeline:
1. **Automated Fetching:** Uses the `kagglehub` library to pull the data directly into the environment.
2. **Data Validation:** Checks for missing values and ensures data types are correct for 31 features.
3. **Anomaly Analysis:** Visualizes the distribution of transaction amounts and times to highlight differences between genuine and fraudulent behavior.
4. **Correlation Mapping:** Uses a heatmap to identify which PCA components are most strongly associated with fraud.
5. **Evaluation Strategy:** Discusses why **AUPRC (Area Under the Precision-Recall Curve)** is used instead of standard accuracy due to the extreme class imbalance.



## 🚀 How to Run
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/credit-card-fraud-detection-analysis.git](https://github.com/your-username/credit-card-fraud-detection-analysis.git)
