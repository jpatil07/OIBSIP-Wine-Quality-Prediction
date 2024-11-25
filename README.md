Project: Wine Quality Prediction with Classification Models
This project predicts the quality of wine based on various features such as alcohol content, acidity, and pH levels using classification algorithms.

Key Steps:
Data Exploration:

Visualized the class distribution of wine quality.
Explored the dataset to understand the features.
Data Preprocessing:

Normalized the features using StandardScaler.
Balanced the dataset using SMOTE (Synthetic Minority Over-sampling Technique) for better performance.
Model Building & Evaluation:

Trained three models:
Random Forest Classifier
Stochastic Gradient Descent (SGD)
Support Vector Classifier (SVC)
Hyperparameter tuning for Random Forest using RandomizedSearchCV.
Model Performance:

Evaluated models using accuracy scores and classification reports.
Performed cross-validation on the Random Forest model.
Visualized confusion matrices for each model.
Feature Importance:

Analyzed feature importance using Random Forest and visualized the results.
Tools & Libraries:
Python: Pandas, NumPy, Seaborn, Matplotlib
Machine Learning: Scikit-learn (RandomForest, SGD, SVC, GridSearchCV, Cross-validation)
Data Balancing: Imbalanced-learn (SMOTE)
