
Hely
Project Title:
Comparative Analysis of Machine Learning Models for Binary and Multiclass Classification

Overview:
This project explores two machine learning problems:
1. Binary Classification - Spam Email Detection
2. Multiclass Classification - Student Academic Performance Prediction

The code includes data preprocessing, feature scaling, class balancing (SMOTE),
model training, hyperparameter tuning, performance evaluation, and visualization.

Datasets:
- Email Dataset: TF-IDF transformed features for spam classification
- Student Dataset: Academic performance with categorical and numeric features

Implemented Models:
- Binary (Spam): Naive Bayes, Support Vector Machine (SVM), Logistic Regression
- Multiclass (Student): Decision Tree, Random Forest, Logistic Regression, Naive Bayes

Key Features of the Code:
Preprocessing pipelines for both datasets
SMOTE for class imbalance correction
Hyperparameter tuning (GridSearchCV for SVM, Decision Trees, etc.)
Confusion Matrix and Classification Reports
ROC Curves, Accuracy Bar Charts, and Learning Curves
Code modularity and separation of tasks by dataset type

How to Run (Google Colab):
1. Open `Phase3_ML_Project_HelyShah.ipynb` in Google Colab.
2. Ensure required libraries are installed using pip commands where necessary.
3. Run each cell sequentially for setup, training, evaluation, and visualization.

Required Libraries:
- scikit-learn
- matplotlib
- seaborn
- pandas
- numpy
- imblearn
\=
Results Summary:
- Best Binary Model: SVM achieved highest accuracy and AUC on the email dataset.
- Best Multiclass Model: Random Forest outperformed others in the student dataset
  in terms of accuracy and robustness.

Credits:
- Developed by: Hely Shah
- Tools used: Google Colab, Python, scikit-learn, pandas, matplotlib

Notes:
Please ensure all required packages are installed before running the notebook.
For academic use and evaluation only.
