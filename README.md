# 🧠 Uncertainty-Aware Disease Risk Prediction Under Noisy and Outlier-Rich Medical Data

## 📌 Project Overview

Medical datasets often contain noise, missing values, and outliers that can significantly affect model performance and reliability. Traditional machine learning models provide predictions but fail to quantify uncertainty — which is critical in healthcare decision-making.

This project aims to develop a robust disease risk prediction system that remains reliable under noisy conditions while incorporating uncertainty estimation techniques to improve trustworthiness.

---

## 🎯 Problem Statement

To build a machine learning model capable of:

- Predicting disease risk from structured medical data  
- Handling noisy and outlier-rich datasets effectively  
- Quantifying predictive uncertainty  
- Evaluating robustness under data perturbations  

---

## 📚 Background & Motivation

In healthcare applications, incorrect predictions can lead to severe consequences. Medical datasets:

- Often contain missing values  
- Include measurement errors  
- May have class imbalance  
- Contain outliers due to abnormal physiological readings  

Therefore, uncertainty-aware models are crucial for:

- Clinical decision support  
- Risk stratification  
- Safe AI deployment in healthcare  

---

## 📂 Dataset

Proposed datasets (subject to feasibility analysis):

- Indian Liver Patient Dataset (ILPD)  
- MIDAS Medical Imaging Dataset  
- Other publicly available medical datasets  

The dataset will be analyzed for:

- Missing values  
- Outliers  
- Class imbalance  
- Noise characteristics  

---

## 🛠 Methodology

### 1️⃣ Data Preprocessing

- Missing value imputation  
- Outlier detection (IQR / Z-score / Isolation Forest)  
- Feature scaling  
- Train-test split  

### 2️⃣ Baseline Models

- Logistic Regression  
- Random Forest  
- XGBoost  

### 3️⃣ Uncertainty Estimation Techniques

- Monte Carlo Dropout  
- Probability Calibration  
- Confidence Interval Analysis  

### 4️⃣ Robustness Evaluation

- Performance under synthetic noise injection  
- Outlier stress testing  
- Calibration curve analysis  

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  
- Brier Score  
- Expected Calibration Error (ECE)  

---

## 📅 Timeline & Milestones

| Phase | Task | Duration |
|-------|------|----------|
| Phase 1 | Literature Review & Problem Finalization | Week 1 |
| Phase 2 | Data Collection & EDA | Week 2 |
| Phase 3 | Data Preprocessing | Week 3 |
| Phase 4 | Baseline Model Development | Week 4–5 |
| Phase 5 | Uncertainty Modeling | Week 6 |
| Phase 6 | Robustness Testing | Week 7 |
| Phase 7 | Documentation & Submission | Week 8 |

---

## 📁 Repository Structure
├── data/
├── notebooks/
├── src/
│ ├── preprocessing.py
│ ├── models.py
│ ├── uncertainty.py
│ └── evaluation.py
├── results/
├── requirements.txt
├── README.md
└── LICENSE

---

## ⚙️ Tech Stack

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  
- PyTorch (if Bayesian methods implemented)  

---

## 🚀 Expected Outcomes

- Robust disease prediction model  
- Improved performance under noisy conditions  
- Reliable uncertainty estimation  
- Reproducible research pipeline  

---

## 👥 Team Members

- Sonu Shaw  
- Anshuman Ray
- Ayushi Mitra
- Saptarshi Dey
- Farhan Gazi
