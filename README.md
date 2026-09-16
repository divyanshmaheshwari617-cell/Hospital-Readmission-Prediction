# Hospital Readmission Prediction

## Objective
To predict hospital patient readmission using **Logistic Regression with L2 Regularization**.

## Dataset
Hospital Patient Records Dataset from Kaggle.

Dataset:
https://www.kaggle.com/datasets/sathwiknomula/hospital-patient-records-dataset

## Features Used
- Age
- Gender
- Condition
- Length of Stay
- Satisfaction
- Total Cost

**Target:** Readmission

## Method
1. Data preprocessing
2. Label Encoding of target
3. StandardScaler for numerical features
4. OneHotEncoder for categorical features
5. Train-Test Split
6. Logistic Regression with L2 Regularization
7. Model Evaluation

## Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC

## Clinical Interpretation
False Negatives are important because a high-risk patient may be incorrectly classified as low-risk, resulting in missed monitoring or intervention.

False Positives mainly result in unnecessary monitoring and resource utilization.

## Technologies
Python, Pandas, Scikit-learn, Matplotlib, KaggleHub
