# Creditcard_Fraud_Detection_MLProject

The goal of this project is to develop a machine learning model that can accurately detect fraudulent credit card transactions using historical data. By analyzing transaction patterns, the model should be able to distinguish between normal and fraudulent activity, helping financial institutions flag suspicious behavior early and reduce potential risks.

Challenges include:

Handling imbalanced datasets where fraud cases are a small fraction of total transactions.
Ensuring high precision to minimize false positives (flagging a valid transaction as fraud).
Ensuring high recall to detect as many fraud cases as possible.

Model use to train is :
**RandomForestClassifier**--> RandomForestClassifier is a supervised machine learning algorithm used for classification tasks. It is an ensemble learning method that builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting.
Instead of relying on a single decision tree, Random Forest creates many trees and uses majority voting to determine the final output.

Steps:
Step 1: Importing necessary Libraries
Step 2: Loading the Data
Step 3: Analyzing Class Distribution
Step 4: Exploring Transaction Amounts
Step 5: Plotting Correlation Matrix
Step 6: Preparing Data
Step 7: Building and Training the Model
Step 8: Evaluating the Model
