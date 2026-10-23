# Task 3: Predictive Customer Churn Classifier

## Project Overview
This project predicts customer churn using telecom customer subscription records. It compares Random Forest and XGBoost classifiers while addressing class imbalance and evaluating model performance using ROC-AUC and other classification metrics.

## Objectives
- Predict whether a customer will leave the telecom service.
- Preprocess categorical and numerical features.
- Convert `TotalCharges` to numeric and handle missing values.
- Address class imbalance using SMOTE or class weighting.
- Train and compare Random Forest and XGBoost models.
- Evaluate performance using ROC-AUC, precision, recall, F1-score, and a confusion matrix.
- Identify the top 10 most influential features.

## Dataset
**Telco Customer Churn Dataset**

Source: [Download Dataset](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)

The dataset contains telecom customer information, subscription details, service usage, and churn labels.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE, if used)
- XGBoost
- Jupyter Notebook / Google Colab

## Methodology
1. Load and explore the dataset.
2. Clean the data and convert `TotalCharges` to numeric.
3. Handle missing values and preprocess categorical features using OneHotEncoder.
4. Split the data into training and testing sets.
5. Address class imbalance using SMOTE or class weighting.
6. Train Random Forest and XGBoost classifiers.
7. Use cross-validation and compare model performance.
8. Plot ROC curves and confusion matrices.
9. Visualize the top 10 feature importances.

## Evaluation Metrics
- ROC-AUC
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

**Target:** ROC-AUC greater than 0.80, subject to experimental results.

## Repository Structure
```text
Task_3_Customer_Churn_Classification/
├── Task_3_Customer_Churn_RandomForest_XGBoost.ipynb
├── README.md
└── visualizations/
    ├── roc_curve.png
    ├── confusion_matrix.png
    └── feature_importance.png
```

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries if they are not already available.
3. Load the dataset from the provided source.
4. Run the notebook cells in order.
5. Review the evaluation metrics and visualizations.

## Deliverables
- Jupyter Notebook containing preprocessing, model training, and evaluation.
- ROC curve.
- Confusion matrix.
- Feature importance bar chart.

## Author
Md. Absar

Machine Learning and Data Science Internship
