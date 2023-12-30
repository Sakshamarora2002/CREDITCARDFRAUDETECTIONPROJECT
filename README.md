# Credit Card Fraud Detection Project

## Overview
This project aims to build a machine learning model for detecting credit card fraud using the Random Forest algorithm. The dataset used in this project contains features like time, transaction amount, and various anonymized features (V1, V2, ..., V28).

## Dataset
The dataset is stored in the file `creditcard.csv` and contains the following columns:
- 'Time'
- 'V1' through 'V28'
- 'Amount'
- 'Class' (0 for legitimate transactions, 1 for fraud)

## Project Structure
- `creditcard.csv`: Dataset file.
- `credit_card_fraud_detection.ipynb`: Jupyter Notebook or Python script containing the code for the project.
- `README.md`: This file, providing an overview of the project.

## Dependencies
- Python 3
- pandas
- scikit-learn

How to Run
1.Clone the repository
git clone <repository_url>
cd <repository_directory>
2.Install the required dependencies.
3.Open and run the credit_card_fraud_detection.ipynb notebook or execute the Python script.


Code Explanation
credit_card_fraud_detection.ipynb contains the code for:
Loading and exploring the dataset.
Preprocessing the data, including scaling features.
Selecting the best features using the chi-squared test.
Training a Random Forest classifier.
Evaluating the classifier's performance.




