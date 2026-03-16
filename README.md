# ML_PROJECT_FRAUD_DETECTION

Overview


This project builds a Machine Learning-based Fraud Detection System that analyzes transaction behavior to identify fraudulent activities.
The system predicts whether a transaction is Fraudulent or Legitimate and generates a Fraud Risk Score (0–100) to categorize the transaction risk level.


Objective

The goal of this project is to:
Detect fraudulent transactions using machine learning
Handle imbalanced datasets
Analyze transaction behavior patterns
Generate a risk score for each transaction
Provide recommendations based on risk level


Dataset

A synthetic dataset was generated to simulate real-world online transactions.
Features
TransactionID
TransactionAmount
TransactionTime
UserAge
UserLocation
DeviceType
PaymentMethod
AccountAge
TransactionFrequency
IsInternational
PreviousFraudHistory


Data Preprocessing

Key preprocessing steps included:
Handling missing values
Encoding categorical variables
Feature scaling using StandardScaler
Handling class imbalance using SMOTE
Exploratory Data Analysis
EDA was performed to identify patterns and trends in fraudulent transactions.



Key visualizations include:

Fraud vs Non-Fraud distribution
Correlation heatmap
Transaction amount distribution
Fraud rate by payment method
Fraud rate by international transactions
Machine Learning Models
The following models were trained and compared:
Logistic Regression
Random Forest
Gradient Boosting
Model performance was


 evaluated using:

Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Confusion Matrix
Fraud Risk Scoring
Instead of only classifying fraud, the model generates a risk score (0–100) based on predicted probability.
Interactive Prediction


 Interface

A console-based interface allows users to input transaction details such as:
Transaction Amount
Payment Method
International Transaction (0/1)
Transaction Frequency
Previous Fraud History
The system then outputs:
Fraud probability
Risk score
Risk category
Recommendation message


Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Imbalanced-learn (SMOTE)


Key Takeaways

Fraud datasets are highly imbalanced, making metrics like Recall and F1-score more important than accuracy.
Feature engineering and proper preprocessing significantly improve fraud detection performance.
Risk scoring systems provide better insights than simple binary classification.
