# Breast Cancer Classification Using Machine Learning and SHAP Explainability

## Project Overview

This project explores how machine learning can be used to classify breast tumors as malignant or benign using the Wisconsin Breast Cancer Dataset.

In addition to building a predictive model, the project focuses on understanding which biological features most influence the model’s decisions through SHAP explainability analysis.

The workflow includes:
- exploratory data analysis
- feature correlation analysis
- logistic regression modeling
- model evaluation
- SHAP-based explainability

## Dataset

The dataset contains:
- 569 samples
- 30 numerical diagnostic features

## Model Performance

The Logistic Regression model achieved approximately:
- 96% accuracy
- strong precision and recall across both classes

## Explainability

SHAP (SHapley Additive exPlanations) was used to identify the features that contributed most strongly to predictions.

Some of the most influential features included:
- worst area
- mean perimeter
- mean area
- mean radius

These findings align with known clinical indicators used in breast cancer diagnosis.

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- SHAP
- Jupyter Notebook

## Author

Hind