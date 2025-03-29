# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. The goal is to develop a model that can accurately distinguish between legitimate and fraudulent transactions to minimize financial loss and improve security.

## Features
- **Supervised Learning Approach**
- **Data Preprocessing & Feature Engineering**
- **Exploratory Data Analysis (EDA)**
- **Model Training and Evaluation**
- **Prediction on New Transactions**

## Dataset
The dataset used is a publicly available **Credit Card Fraud Detection** dataset, which contains:
- **284,807 transactions**
- **30 numerical features** (including PCA-transformed features)
- **2 classes**:
  → Legitimate transactions
  → Fraudulent transactions
- The dataset is highly imbalanced, with only **0.17% fraudulent transactions**.

## Technologies Used
- Python
- Pandas & NumPy (Data Processing)
- Matplotlib & Seaborn (Data Visualization)
- Scikit-learn (Machine Learning Models)


## Model Training
Several machine learning models were implemented and evaluated, including:
- Logistic Regression
  
## Handling Imbalanced Data
Since fraudulent transactions are rare, techniques such as:
- **Oversampling (SMOTE - Synthetic Minority Over-sampling Technique)**
- **Undersampling the majority class**
- **Cost-sensitive learning**
were used to improve model performance.

## Installation
To run the project, install the required dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost
```

## Usage
Run the Python script to train the model and make predictions:
```bash
python fraud_detection.py
```

## Results
The model achieved high precision and recall in detecting fraudulent transactions while minimizing false positives.

## Conclusion
This project demonstrates the effectiveness of Machine Learning in detecting fraudulent transactions, with a focus on handling imbalanced datasets and improving prediction accuracy.

## Acknowledgment
This project is based on publicly available credit card fraud detection datasets, primarily from **Kaggle**.



