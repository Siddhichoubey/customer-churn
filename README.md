Customer Churn Prediction using ANN
Project Overview
This project focuses on identifying potential churn customers for a banking institution. It
utilizes deep learning techniques, specifically an Artificial Neural Network (ANN), to predict
whether a customer will exit the bank based on various demographic and financial factors.
Dataset
The project uses the Churn_Modelling.csv dataset, which includes 10,000 customer records
with the following key features:
 CreditScore: Numerical value representing creditworthiness.
 Geography: Customer's location (e.g., France, Spain, Germany).
 Gender: Male or Female.
 Age: Customer's age.
 Tenure: Number of years with the bank.
 Balance: Account balance.
 NumOfProducts: Number of products the customer uses.
 HasCrCard: Whether the customer has a credit card (Binary).
 IsActiveMember: Whether the customer is an active member (Binary).
 EstimatedSalary: Customer's annual salary.
 Exited: Target variable (1 if churned, 0 otherwise).
Technical Workflow
1. Data Loading & EDA: Importing data using pandas and performing Exploratory
Data Analysis to identify null values and understand feature distributions.
2. Preprocessing: Handling categorical data (Geography and Gender) and scaling
numerical features to prepare them for the neural network.
3. Model Architecture: Implementing a sequential ANN model using
TensorFlow/Keras.
4. Training: The model is trained on a subset of the data to learn complex non-linear
patterns associated with customer churn.
5. Evaluation: Assessing model performance using standard metrics and visualizing the
network architecture.
Requirements
 Python 3.x
 Pandas, NumPy
 Matplotlib, Seaborn
 TensorFlow/Keras
