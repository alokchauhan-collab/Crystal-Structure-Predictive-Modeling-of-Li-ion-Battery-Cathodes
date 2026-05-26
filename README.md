# Crystal-Structure-Predictive-Modeling-of-Li-ion-Battery-Cathodes
Machine learning framework for crystal system prediction of lithium-ion battery materials using ensemble learning, SMOTE-based preprocessing, hyperparameter optimization, and SHAP explainability analysis for interpretable materials informatics and crystal structure classification.
Crystal System Prediction Using Machine Learning
Overview

This repository presents a machine learning framework for predicting crystal system classes of lithium-ion battery materials using ensemble learning and explainable artificial intelligence (XAI) techniques. The workflow integrates data preprocessing, feature engineering, class balancing, hyperparameter optimization, ensemble classification, and SHAP-based interpretability analysis.

Features
Crystal system classification using machine learning
Ensemble learning with stacking classifiers
Hyperparameter optimization using RandomizedSearchCV
Data balancing using SMOTE
SHAP explainability analysis for feature contribution
ROC curves and confusion matrix visualization
Reproducible experimental workflow
Machine Learning Models

The following models were implemented and evaluated:

Random Forest
XGBoost
CatBoost
Gradient Boosting
AdaBoost
Decision Tree
K-Nearest Neighbors
Support Vector Machine
Logistic Regression
Gaussian Naive Bayes
Stacking Ensemble Classifier
Dataset

The dataset contains lithium-ion battery material descriptors and crystal system labels used for supervised classification.

Data Preprocessing

The preprocessing pipeline includes:

Missing value imputation
Feature scaling
Label encoding
Stratified train-test split
SMOTE-based class balancing
Experimental Setup
Python environment using Jupyter Notebook
Scikit-learn, XGBoost, CatBoost, SHAP, and Imbalanced-learn libraries
80:20 train-test split
Random seed fixed at 42
Cross-validation for model optimization
Evaluation Metrics

Model performance was evaluated using:

Accuracy
Precision
Recall
F1-score
ROC-AUC
Confusion matrix
Explainability

SHAP (SHapley Additive exPlanations) was used to analyze feature importance and interpret model predictions for crystal system classification.

Repository Structure
├── optimized_lithium_battery_model.ipynb
├── lithium-ion batteries.csv
├── requirements.txt
└── README.md
Installation

Install the required dependencies using:

pip install -r requirements.txt
Usage

Run the Jupyter Notebook:

jupyter notebook optimized_lithium_battery_model.ipynb
Reproducibility

The repository includes preprocessing steps, model configurations, optimization settings, and interpretability analysis to facilitate reproducible research.

Citation

If you use this work in your research, please cite the associated publication.

License

This project is intended for academic and research purposes.
