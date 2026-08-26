# Handling Class Imbalance in Diabetes Prediction

## Overview
This project addresses severe class imbalance in the *Pima Indians Diabetes Dataset* to improve the reliability of predicting diabetic patients. The goal is to maximize sensitivity (recall) for positive cases without sacrificing overall model performance.

## Imbalance Handling Techniques
* *Resampling:* Undersampling, Oversampling, SMOTE
* *Algorithmic:* Class Weighting, Balanced Random Forest, Easy Ensemble

## Models & Evaluation
* *Algorithms Trained:* Logistic Regression, Support Vector Machine (SVM), XGBoost
* *Evaluation Metrics:* ROC-AUC, F1-Score, Recall

## Key Results
* *SMOTE* and ensemble methods significantly improved recall for the diabetic class.
* Achieved an approximate *60% boost in recall* over baseline models while maintaining overall accuracy.
* Model performance trade-offs were evaluated using ROC curve visualizations.

## Key Takeaway
Properly handling class imbalance is crucial in domain-specific applications like healthcare, where missing a positive diagnosis (False Negative) has critical real-world consequences.

## Project Structure
```text
├── notebook.ipynb     # Google Colab notebook containing full pipeline
└── README.md          # Project documentation
