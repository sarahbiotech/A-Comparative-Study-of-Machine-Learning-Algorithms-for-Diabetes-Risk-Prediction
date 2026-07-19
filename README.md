# Diabetes Prediction Using Machine Learning

## Overview
This project develops a machine learning model to predict diabetes risk based on medical diagnostic measurements. The goal is to compare different classification algorithms and identify the model with the best predictive performance.

## Dataset
The project uses the **Pima Indians Diabetes Dataset**, which contains health-related features:

- Pregnancies
- Glucose level
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

**Target variable:**
- `Outcome`
  - 0: Non-diabetic
  - 1: Diabetic

## Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Joblib

## Machine Learning Models
The following classification algorithms were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVC)
- Random Forest Classifier

## Workflow
1. Load and explore the dataset.
2. Perform correlation analysis and data visualization.
3. Split data into training and testing sets.
4. Train multiple machine learning models.
5. Evaluate performance using:
   - Accuracy
   - F1-score
   - Recall
   - Confusion Matrix
6. Save trained models for future predictions.

## Results

| Model | Accuracy | F1-score | Recall |
|---|---|---|---|
| Logistic Regression | 75.32% | 59.57% | 52.83% |
| SVC | 73.38% | 52.87% | 43.40% |
| Random Forest | 72.73% | 57.14% | 52.83% |

**Best performing model:** Logistic Regression, achieving the highest accuracy and F1-score.

## Saved Models
The trained models were exported using Joblib:

- `logistic_model.pkl`
- `svm_model.pkl`
- `random_forest_model.pkl`

## Future Improvements
- Apply feature scaling and advanced preprocessing.
- Optimize hyperparameters.
- Address class imbalance.
- Deploy the model using a web application.

## Author
**Sarah Ali**  
Biochemistry | Computational Biology | Machine Learning
