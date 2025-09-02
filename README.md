# MLproject
Machine learning project to predict student satisfaction with AI-assisted learning.

This project applies machine learning techniques to predict students’ satisfaction with AI-assisted learning tools.
The pipeline includes:

- Data preprocessing with tailored imputers, scalers, and encoders (via ColumnTransformer).

- Handling class imbalance using oversampling techniques such as SMOTE.

- Dimensionality reduction with PCA to remove noise and redundancy.

- Model selection and evaluation (Logistic Regression as baseline, with hyperparameter tuning via GridSearch/RandomizedSearch).

The goal is to build an end-to-end, reproducible workflow that addresses real-world challenges such as missing values, heterogeneous features, and imbalanced data.
