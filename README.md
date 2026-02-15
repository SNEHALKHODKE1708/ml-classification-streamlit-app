🧠 Problem Statement

The objective of this project is to implement and compare multiple machine learning classification models on a real-world dataset and deploy the solution as an interactive Streamlit web application.

The goal is to evaluate model performance using multiple evaluation metrics and identify the best-performing model.

📊 Dataset Description

Dataset Name: Breast Cancer Wisconsin Dataset

Source: Scikit-learn / Public Repository

Total Instances: 569

Total Features: 30

Target Variable: Binary classification (Malignant = 0, Benign = 1)

The dataset contains numerical features extracted from digitized images of breast mass tissue samples.

🤖 Machine Learning Models Implemented

Logistic Regression

Decision Tree

K-Nearest Neighbors

Naive Bayes

Random Forest (Ensemble)

XGBoost (Ensemble)

📈 Evaluation Metrics Used

Each model was evaluated using:

Accuracy

AUC Score

Precision

Recall

F1 Score

Matthews Correlation Coefficient (MCC)

📊 Model Comparison Table

(Paste your actual result table here)

Example format:

Model	Accuracy	AUC	Precision	Recall	F1	MCC
Logistic Regression	0.97	0.99	...	...	...	...
🔍 Observations

Logistic Regression achieved the highest overall accuracy and AUC.

Decision Tree showed slightly lower MCC due to possible overfitting.

KNN performed well after feature scaling.

Naive Bayes demonstrated stable probabilistic performance.

Random Forest improved generalization.

XGBoost showed strong ensemble performance with high AUC.

(Rewrite slightly in your own words.)

🌐 Streamlit Application Features

The deployed Streamlit application includes:

CSV dataset upload option

Model selection dropdown

Prediction generation

Display of confusion matrix

🚀 Deployment

The application is deployed using Streamlit Community Cloud and connected with GitHub repository.
