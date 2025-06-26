
# Credit Card Fraud Detection

This project investigates various machine learning methods to detect fraudulent credit card transactions in a **highly imbalanced dataset**. It includes data cleaning, balancing techniques, and model comparison to identify the most effective fraud detection approach.

---

## Project Objectives

- Detect fraudulent credit card transactions using machine learning.
- Handle class imbalance using advanced resampling methods.
- Minimise false positives and false negatives to improve model performance.
- Compare multiple classification algorithms using standard evaluation metrics.

---

## Methods and Workflow

1. **Descriptive Analysis**
   - Initial data exploration and duplication removal.
   - Summary statistics and class distribution analysis.

2. **Data Preprocessing**
   - Balancing the dataset using:
     - SMOTE (Synthetic Minority Oversampling Technique)
     - NearMiss (Undersampling)
     - SMOTE-ENN (Hybrid Oversampling and Undersampling)

3. **Dimensionality Reduction**
   - Applied **Linear Discriminant Analysis (LDA)** to reduce features while preserving class separation.

4. **Model Training & Evaluation**
   - Trained and compared the following models:
     - Logistic Regression
     - Random Forest Classifier
     - XGBoost Classifier
   - Evaluated models using:
     - Accuracy
     - Precision
     - Recall
     - F1 Score
     - Confusion Matrix
     - ROC-AUC Score

---

## Project Outputs

- Cleaned and balanced the dataset.
- Visual analysis of model performance (via Matplotlib & Seaborn).
- Comparison of model metrics to determine the most effective fraud detection approach.

---

## Technologies and Tools

### Environment
- Python 3.x
- Google Colab

### Libraries
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `imbalanced-learn`
- `xgboost`

---


## License

This project is licensed under the [MIT License].
