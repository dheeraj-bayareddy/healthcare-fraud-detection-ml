
# Health Insurance Fraud Detection using Machine Learning

## Project Overview
This project focuses on detecting fraudulent health insurance claims using supervised machine learning techniques. The dataset used contains synthetic healthcare insurance claim records designed for fraud detection research and experimentation.

## Dataset Information
- **Dataset Title:** Synthetic Health Insurance Claims Fraud Detection
- **Domain:** Healthcare / Insurance Fraud Detection
- **Dataset Source:** https://www.kaggle.com/datasets/mahfuz95/synthetic-health-insurance-claims-fraud-detection
- **Rows:** 1,000,000
- **Columns:** 30

## Dataset Description
This dataset contains synthetic health insurance claim records created for fraud detection and machine learning applications. It represents real-world healthcare insurance scenarios, including patient details, treatment information, claim amounts, and provider data.

The dataset includes both genuine and fraudulent claims, making it highly suitable for:
- Supervised Learning
- Classification Tasks
- Fraud Detection
- Anomaly Detection
- Predictive Analytics

---

# Research Questions

## RQ1: Baseline Model Performance
**Objective:** Evaluate baseline supervised learning models such as Logistic Regression, Decision Tree, and KNN.

### Results
- Decision Tree performed better among baseline models.
- Baseline models confirmed strong predictive patterns in the dataset.

---

## RQ2: Advanced Model Comparison
**Objective:** Compare advanced machine learning models including Random Forest, Gradient Boosting, and SGD Classifier.

### Results
- Random Forest and Gradient Boosting achieved high predictive accuracy.
- Ensemble methods outperformed simpler baseline models.

---

## RQ3: Impact of Preprocessing
**Objective:** Analyze how preprocessing affects model performance.

### Results
- Scaling and preprocessing improved model performance.
- Proper preprocessing produced more stable predictions.

---

## RQ4: Feature Importance Analysis
**Objective:** Identify the most influential features contributing to fraud prediction.

### Important Features
- Provider_Patient_Distance_Miles
- Number_of_Previous_Claims_Provider
- Number_of_Procedures
- Number_of_Previous_Claims_Patient

### Results
Feature importance analysis revealed that provider history and claim-related variables strongly influence fraud detection.

---

## RQ5: Metric Sensitivity Analysis
**Objective:** Analyze model performance across different evaluation metrics.

### Results
- Accuracy: 0.9615
- Precision: 0.9793
- Recall: 0.9423
- F1 Score: 0.9604

The model achieved balanced and stable performance across evaluation metrics.

---

## RQ6: Correlation Heatmap Analysis
**Objective:** Examine correlations between important variables.

### Results
Strong positive correlations were observed between:
- Fraudulent claims and provider-patient distance
- Previous provider claims
- Number of procedures

This indicates these variables strongly contribute to fraudulent activity prediction.

---

## RQ7: Fraud Class Distribution Analysis
**Objective:** Analyze the balance between fraudulent and non-fraudulent claims.

### Results
- Fraudulent Claims: 49.6%
- Non-Fraudulent Claims: 50.4%

The dataset is well balanced for classification tasks.

---

# Repository Structure

```bash
healthcare-fraud-detection-ml/
│
├── notebooks/
│   ├── Notebook-0-Preprocessing.ipynb
│   ├── RQ1_baseline_models.ipynb
│   ├── RQ2_model_comparison.ipynb
│   ├── RQ3_Impact_of_preprocessing.ipynb
│   ├── RQ4_feature_importance.ipynb
│   ├── RQ5_metric_sensitivity_analysis.ipynb
│   ├── RQ6_correlation_heatmap_analysis.ipynb
│   └── RQ7_fraud_class_distribution_analysis.ipynb
│
├── README.md
└── LICENSE
```

# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

# Conclusion
The project successfully demonstrates how machine learning techniques can be applied to healthcare insurance fraud detection. Ensemble learning models and proper preprocessing techniques significantly improved predictive performance.

