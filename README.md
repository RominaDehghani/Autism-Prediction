# Autism-Prediction

Project Overview:
This project predicts Autism Spectrum Disorder (ASD) based on various features like test scores and demographics. It utilizes machine learning models like Decision Tree, Random Forest, and XGBoost, with hyperparameter tuning to select the best model.

Files:
Autism_Prediction.ipynb: Jupyter notebook for data processing, model training, and evaluation.
encoders.pkl: Pickle file storing label encoders.
best_model.pkl: Pickle file storing the best trained model.

Install required libraries:
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn xgboost

Steps:
Load and preprocess data: Handle missing values, encode categorical variables, and balance the dataset using SMOTE.
Exploratory Data Analysis (EDA): Visualize distributions and correlations.
Train models: Use Decision Tree, Random Forest, and XGBoost, with cross-validation and hyperparameter tuning.
Evaluation: The best model is selected and evaluated on test data.

How to Run:
Place the train.csv dataset in the correct directory.
Open and run the notebook (Autism_Prediction.ipynb).
The best model is saved as best_model.pkl.
