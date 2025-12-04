# ML-Binary-and-Multiclass-Classification-Project

## Overview
This project implements and compares machine learning models for two different types of problems:
1. **Binary Classification** – Spam vs. Non-Spam Email Detection  
2. **Multiclass Classification** – Student Academic Performance Prediction (grade categories)

The goal is to build end-to-end ML pipelines, from preprocessing to model evaluation and visualization, and to compare how different algorithms perform on binary vs. multiclass tasks.

---

## Datasets

### **Spam Email Dataset**
- File: `emails.csv`
- Target: `spam` (1 = spam, 0 = not spam)
- Text feature: `text` (raw email content)

### **Student Performance Dataset**
- File: `Student_performance_data _.csv`
- Target: `GradeClass` (multiple grade categories)
- Mix of categorical and numerical features.

---

## Models Implemented

### **Binary Classification – Spam Email**
- Logistic Regression  
- Naive Bayes (MultinomialNB)  
- Support Vector Machine (SVM)  
- Random Forest  

### **Multiclass Classification – Student Performance**
- Logistic Regression (multinomial)  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)

---

## Key Techniques

- TF-IDF text vectorization  
- One-hot encoding for categorical variables  
- Feature scaling with StandardScaler  
- Class balancing using SMOTE  
- Hyperparameter tuning using GridSearchCV  
- Evaluation with:
  - F1 Score (binary + macro)
  - Precision  
  - Confusion Matrices  
  - ROC Curves (email dataset)  
  - Training/testing time comparison  
  - Learning curves  
  - Feature importance  

---

## How to Run

1. Keep the following files together:
   - `main.py`
   - `emails.csv`
   - `Student_performance_data _.csv`

2. Install the required Python packages:

```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
