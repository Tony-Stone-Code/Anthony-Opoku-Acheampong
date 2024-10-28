# Credit Card Fraud Detection

This project builds a credit card fraud detection system using machine learning on a highly imbalanced dataset. We used Random Forest for classification and SMOTE to handle data imbalance.

## Dataset
The dataset contains anonymized features (`V1` to `V28`), `Time`, `Amount`, and a `Class` label indicating fraud or non-fraud.

## Key Steps:
1. Data Preprocessing (Scaling, Handling Imbalance).
2. Model Building with Random Forest Classifier.
3. Evaluation with accuracy, precision, recall, F1-score, and ROC-AUC.
4. SMOTE was used to balance the dataset.

## Dependencies:
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib, Seaborn
