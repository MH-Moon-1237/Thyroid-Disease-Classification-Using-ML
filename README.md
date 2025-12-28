# Thyroid-Disease-Classification-Using-ML
Machine Learning-Based Thyroid Disease Classification: Multi-Algorithm Strategy with Enhanced Data Processing

# Thyroid Disease Classification Using Machine Learning

This project presents a machine learning–based framework for multi-class thyroid
disease classification using clinical and laboratory data. Multiple ML models
are compared, with XGBoost achieving the best performance. Robust evaluation and
cross-validation techniques are applied.

---

## 🎯 Project Objective

The objectives of this project are:
- Classify thyroid disease into multiple clinical categories
- Handle class imbalance effectively
- Compare multiple machine learning classifiers
- Ensure robust evaluation using cross-validation and ROC–AUC analysis

---

## 🗂️ Dataset Description

- Dataset: Thyroid Disease Dataset
- Features include TSH, T3, TT4, T4U, FTI, and patient demographic data
- Target variable: Multi-class thyroid disease label

---

## ⚙️ Data Preprocessing

- Missing value imputation using median and most frequent strategies
- Outlier removal using IQR method
- One-hot encoding for categorical features
- Feature selection using ANOVA F-test (SelectKBest)
- Class imbalance handling using SMOTE

---

## 🧠 Machine Learning Models Used

- Logistic Regression
- Gaussian Naive Bayes
- Multi-layer Perceptron (MLP)
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- CatBoost
- XGBoost (Best performing model)

---

## 📊 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC Curve and AUC (One-vs-Rest)
- Training and validation loss & accuracy curves
- **10-Fold Cross Validation**

---

## 🔁 Cross Validation

10-fold cross-validation was applied to evaluate model robustness and
generalization. Mean and standard deviation of accuracy were reported.

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook

