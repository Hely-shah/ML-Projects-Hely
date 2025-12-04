# Spam Email Classification (Binary Classification)

This project predicts whether an email is **spam** or **not spam** using multiple machine learning models.  
It includes preprocessing, TF-IDF vectorization, model training, evaluation, and visualization.

## Dataset
- Binary labeled email dataset (Spam = 1, Not Spam = 0)
- Text features transformed using **TF-IDF**

## Machine Learning Models Used
- **Logistic Regression**
- **Naive Bayes**
- **Support Vector Machine (SVM)**

## Key Steps in the Notebook
- Text cleaning & preprocessing
- TF-IDF feature extraction
- Train-test split
- Model training and comparison
- Confusion matrices & classification reports
- ROC curves for model evaluation
- Accuracy bar charts & learning curves

## Results Summary
- **SVM** achieved the highest accuracy and best ROC-AUC score.
- Logistic Regression and Naive Bayes also performed efficiently with fast training times.

## How to Run
1. Open the notebook: `Spam_Email_Classification.ipynb`
2. Run all cells sequentially
3. Requires Python 3.8+ and the following libraries:
   - scikit-learn
   - pandas
   - numpy
   - matplotlib
   - seaborn

## Project Files
- `Spam_Email_Classification.ipynb` — full code
- `report.pdf` — project report
- `presentation.pdf` — slides explaining methodology & results

## Author
**Hely Shah**  
MS in Computer Science, Hofstra University  
Project developed using Google Colab & Python.
