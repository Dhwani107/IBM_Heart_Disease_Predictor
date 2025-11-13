# IBM_Heart_Disease_Predictor

Heart Disease Prediction using Logistic Regression

This project builds a Machine Learning model that predicts whether a person has heart disease based on clinical features.
A Logistic Regression model is trained using the Heart Disease UCI dataset.
The script also generates evaluation metrics and visualizations to understand model performance.

🚀 Features

✔ Logistic Regression model for binary classification
✔ Preprocessing pipeline (scaling + encoding)
✔ Train/validation/test split
✔ Threshold optimization using Youden’s J statistic
✔ Evaluation metrics:

Accuracy
Precision
Recall
F1 Score
ROC-AUC

✔ Visualizations:

Class Balance chart
ROC Curve
Confusion Matrix
ML Pipeline Flowchart

✔ Saves trained model as .joblib

🧠 How It Works

Load heart.csv dataset
Identify categorical and numerical features
Preprocess using:
Median imputation
Standard scaling
One-hot encoding
Train Logistic Regression model
Compute and print all performance metrics
Save graphs as PNG files
Save trained model to /artifacts/heart_logreg_pipeline.joblib
Run a final prediction test on a sample patient



▶️ Running the Project

Make sure required libraries are installed:
pip install pandas numpy scikit-learn matplotlib joblib


Run the script:
python heartdisease.py

📊 Outputs Generated

class_balance.png – shows dataset distribution
roc_curve_test.png – model ROC curve
confusion_matrix_test.png – confusion matrix
ml_pipeline_flowchart.png – ML pipeline steps
artifacts/heart_logreg_pipeline.joblib – trained model

✔ Technologies Used

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Joblib
