🛡️ System Threat Detection with Machine Learning
A machine learning-based approach to detect potential system security threats by classifying system events as malicious or benign using behavioral and log data. Built for a Kaggle competition, this project demonstrates model development, feature selection, and hyperparameter tuning.
🚨 What This Project Does
This project builds and evaluates ML models that predict whether a given system activity (based on numerical/log features) poses a security threat. It simulates how ML can assist in cybersecurity by identifying abnormal patterns in system behavior.
📂 Dataset
The dataset includes anonymized features extracted from system logs, such as:
Process and system activity metrics
File, network, and registry events
Binary indicators of known threat behaviors
The target is a binary label:
1 = Threat
0 = Normal activity
🧠 Models Used
Three supervised learning models were implemented and compared:
Logistic Regression
Random Forest Classifier
XGBoost Classifier
Each model was trained, tuned, and evaluated for performance.
🔍 Key Techniques
Data Preprocessing: Null handling, scaling, encoding
Feature Selection:
SelectKBest (Univariate statistical tests)
SelectFromModel (Model-based importance)
Model Tuning: GridSearchCV for hyperparameter optimization
Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC
