# Crystal-Structure-Predictive-Modeling-of-Li-ion-Battery-Cathodes
Machine learning framework for crystal system prediction of lithium-ion battery materials using ensemble learning, SMOTE-based preprocessing, hyperparameter optimization, and SHAP explainability analysis for interpretable materials informatics and crystal structure classification.
# Crystal System Prediction Using Machine Learning
Overview
This repository presents a machine learning framework for predicting crystal system classes of lithium-ion battery materials using ensemble learning and explainable artificial intelligence (XAI) techniques. The workflow integrates data preprocessing, feature engineering, class balancing, hyperparameter optimization, ensemble classification, and SHAP-based interpretability analysis.

# Crystal System Prediction Using Machine Learning

## Overview
This repository presents a machine learning framework for predicting crystal system classes of lithium-ion battery materials using ensemble learning and SHAP-based explainability analysis.

## Features
- Crystal system classification
- Ensemble learning models
- Hyperparameter optimization
- SMOTE-based class balancing
- SHAP feature importance analysis
- ROC and confusion matrix visualization

## Models Used
- Random Forest
- XGBoost
- CatBoost
- Gradient Boosting
- Logistic Regression
- Stacking Ensemble

## Dataset
The dataset contains lithium-ion battery material descriptors and crystal system labels for supervised classification.

## Experimental Setup
- Python and Jupyter Notebook
- Scikit-learn, XGBoost, CatBoost, SHAP
- 80:20 train-test split
- Random seed = 42
- SMOTE for imbalance handling

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Repository Structure
```text
├── optimized_lithium_battery_model.ipynb
├── lithium-ion batteries.csv
├── requirements.txt
└── README.md

## Reproducibility

The repository includes preprocessing steps, model configurations, optimization settings, and interpretability analysis to facilitate reproducible research.

## Citation

If you use this work in your research, please cite the associated publication.

## License

This project is intended for academic and research purposes.
