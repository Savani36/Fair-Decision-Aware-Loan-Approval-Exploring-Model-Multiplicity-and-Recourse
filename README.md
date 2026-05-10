# Fair Decision-Aware Loan Approval System

## Overview
This project explores how different machine learning models with similar predictive performance can produce different decisions in financial applications.

The project investigates:
- Model multiplicity
- Fairness in loan approval systems
- Decision-aware evaluation
- Basic recourse analysis
## Dataset Source

This project uses the UCI Statlog German Credit Dataset accessed via the ucimlrepo package for reproducible data retrieval.
Dataset:
UCI Statlog German Credit Dataset (https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest

## Key Findings
- Models achieved similar accuracy scores
- Approval decisions differed across models
- Fairness metrics varied significantly
- Small feature changes could alter outcomes

## Technologies
Python, Scikit-learn, Pandas, Matplotlib

## Future Improvements
- SHAP explainability
- Counterfactual recourse
- Fairlearn integration
- Decision-focused optimisation
