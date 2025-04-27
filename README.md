# Wine Quality Prediction Project
## 📖 Project Overview
This project focuses on evaluating and comparing multiple machine learning models to predict the quality of white wines based on physicochemical tests.
The Wine Quality dataset was analyzed, and several classification models were built and compared to determine the best-performing algorithm.

## 📂 Dataset
Source: Wine Quality Dataset (White Wine)

Rows: 4898

Columns: 12

Target Variable: quality (binarized into Good (1) and Not Good (0))

## 🛠️ Main Steps
Data Preprocessing

Handling missing values (none present)

Data visualization and exploration

Feature selection based on correlation and feature importance

Feature scaling (Min-Max Scaler)

Data partitioning (Train/Test split)

Feature Engineering

Created a binary target variable (quality_binary)

Selected important features: alcohol, density, chlorides, volatile acidity, total sulfur dioxide

Model Training and Evaluation

## Models Trained:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Gradient Boosting Classifier

SMOTE (Synthetic Minority Over-sampling Technique) was applied to handle class imbalance.

## Evaluated models using:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

Results Visualization

Plotted confusion matrices

Compared model performances using bar charts

## 🧪 Model Comparison Results

Model	Accuracy
Random Forest	78.7%
Gradient Boosting	78.3%
K-Nearest Neighbors (KNN)	77.8%
Support Vector Machine	76.7%
XGBoost	74.3%
Logistic Regression	70.2%
## ✅ Random Forest Classifier achieved the highest accuracy!

## 📈 Technologies Used
- Python 3

- Pandas

- Matplotlib & Seaborn

- Scikit-learn

- XGBoost

- Imbalanced-learn (SMOTE)


## 📬 Contact
For questions or collaborations, feel free to connect with me at shakera.sahee@gmail.com.
