# Loan Default Prediction Using Machine Learning

## Project Overview
This project develops a machine learning model to predict whether a borrower is likely to default on a loan. The project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, explainability, fairness analysis, and ethical considerations.

The objective is to help financial institutions identify high-risk borrowers while promoting responsible and transparent AI practices.

---

## Objectives

- Perform exploratory data analysis (EDA).
- Clean and preprocess the dataset.
- Create new features to improve prediction accuracy.
- Train and evaluate a machine learning model.
- Explain model predictions using SHAP.
- Assess fairness across demographic groups.
- Discuss ethical considerations and potential model biases.

---

## Dataset

**Dataset:** Bank Loan Dataset

The dataset contains borrower information, including financial, demographic, and loan-related attributes used to predict loan default.

Target Variable:

- **Default** (Loan Default)

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP

---

## Project Workflow

### 1. Data Analysis and Cleaning

- Loaded the dataset
- Explored data structure
- Generated summary statistics
- Visualized feature distributions
- Handled missing values
- Encoded categorical variables
- Scaled numerical features

### 2. Feature Engineering

- Created additional predictive features
- Standardized numerical variables
- Prepared the dataset for machine learning

### 3. Model Building

- Split data into training and testing sets
- Trained a Random Forest Classifier
- Evaluated model performance

Evaluation metrics include:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score

### 4. Explainability and Fairness

- Generated SHAP explanations
- Analyzed feature importance
- Compared model performance across demographic groups

### 5. Ethical Considerations

The project discusses:

- Fairness
- Privacy
- Transparency
- Bias mitigation strategies
- Responsible AI practices

---

## Results

The Random Forest model successfully predicted loan default using borrower financial information. Feature importance and SHAP analysis identified the variables that most influenced predictions, while fairness analysis highlighted the importance of monitoring model performance across different demographic groups.

---

## Repository Contents

```
Assignment_15.ipynb
README.md
Assignment_15_Ethical_Considerations_Report.docx
Assignment_15_Colab_Style.pdf
```

---

## Author

**Josee Uwamariya**


