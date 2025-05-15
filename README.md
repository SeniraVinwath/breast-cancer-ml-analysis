Cancer Patient Mortality & Survival Prediction - ML Project
This repository contains a collection of three Google Colab notebooks created as part of a Machine Learning coursework project. The project involves two core case studies focused on medical data: one predicting cancer patient mortality status (classification) and the other predicting survival duration in months (regression).

📁 Repository Structure


📂 ML_Project_Repo/
├── NoteBook1_20220997.ipynb
├── NoteBook2_20220997.ipynb
├── NoteBook3_20220997.ipynb
└── README.md


📘 Case Study A: Mortality Status Classification

Objective

Build and evaluate machine learning models to classify whether a breast cancer patient is Alive or Dead based on clinical and demographic data.

Techniques Used
    Data preprocessing (null handling, encoding, normalization)
    Class balancing
    Train-test splitting (60:40, stratified)
    Model training: Naïve Bayes, Logistic Regression, K-Nearest Neighbors
    Hyperparameter tuning with GridSearchCV
    Evaluation metrics: Recall, Precision, F1-Score, AUC-ROC

Key Insights

    Naïve Bayes achieved the best balance between recall and precision, making it the most reliable model for identifying deceased patients.
    Class balancing and feature scaling were critical to improving model fairness and performance.


📗 Case Study B: Survival Months Regression

Objective

Predict the number of months a cancer patient is expected to survive using regression models.

Techniques Used
    Decision Tree Regressor (DT-1: fully grown, DT-2: pre-pruned)
    Model interpretability and decision rules
    Evaluation metrics: MAE, MSE, R²

Key Insights

    MAE was the most informative metric for survival prediction.
    Pre-pruned Decision Tree (DT-2) had better generalization and lower prediction error (MAE = 0.2017).
    High outliers in survival data required careful filtering to maintain model integrity.


📒 Ensemble Model

    This explores ensemble-based comparisons between the three classification models, analyzing their combined performance using voting classifiers and highlighting the advantages of model fusion.

📊 Datasets

The dataset used is related to breast cancer patients and contains features such as:
    Age, Tumor Size, T/N Stages, Estrogen/Progesterone status
    Mortality Status (Classification)
    Survival Months (Regression)

Note: The data was cleaned, normalized, encoded, and balanced prior to model training.


👨‍💻 Author
Juliyan Senira Vinwath Mendis