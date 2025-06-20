# Credit Card Fraud Detection

This project implements a robust machine learning pipeline to detect fraudulent credit card transactions using real-world, highly imbalanced data. The goal is to evaluate multiple classification models, address class imbalance challenges, and improve detection accuracy with advanced techniques like SMOTE and XGBoost tuning.

---

## Problem Statement

Credit card fraud presents a growing threat to financial institutions and consumers alike. With only ~0.17% of all transactions being fraudulent, the challenge lies in accurately identifying these rare events while minimizing false positives.

---

## Methods & Techniques

- Exploratory Data Analysis (EDA)  
- Outlier Detection & Removal (IQR Method)  
- Feature Scaling using RobustScaler  
- Class Imbalance Handling: SMOTE & Random Undersampling  
- Machine Learning Models:
  - Logistic Regression  
  - Support Vector Machines (SVM)  
  - Decision Trees  
  - Random Forest  
  - XGBoost  
  - Voting Classifier (Ensemble)  
- Model Evaluation:
  - ROC AUC
  - Confusion Matrix
  - Precision, Recall, F1-Score


---

## Key Results

- **XGBoost (after fine-tuning)** achieved an AUC score of **0.9921**, significantly outperforming baseline models.
- Fine-tuning reduced both false positives and false negatives, improving model generalization on unseen data.
- Voting Classifier achieved robust performance by combining top individual models.

---

## Technologies Used

- **Languages:** Python  
- **Libraries:** pandas, scikit-learn, imbalanced-learn, matplotlib, seaborn, XGBoost  
- **Notebook:** Jupyter  
- **IDE:** VS Code / Google Colab  

---

##  Dataset

- Source: [Kaggle Credit Card Fraud Dataset]
