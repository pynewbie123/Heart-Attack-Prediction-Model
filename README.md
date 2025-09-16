Machine learning project to predict heart attack risk using health and lifestyle data. Models used include Logistic Regression, Random Forest, XGBoost, and LightGBM, with techniques to handle class imbalance and improve performance.

Dataset: link (https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease?select=2022)

Records: ~400,000

Features: ~40 (demographics, lifestyle, medical history)

Target: Had Heart Attack (Yes/No)

Methods:

Data preprocessing (encoding, scaling, outlier treatment)

Class imbalance handling (undersampling, SMOTE)

Model training & tuning (Logistic Regression, Random Forest, XGBoost, LightGBM)

Results:

Logistic Regression (baseline): 93% accuracy, but low recall for positive cases

Tuned LightGBM: 96% accuracy with better precision–recall balance
