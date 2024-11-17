Online Fraud Detection System
This project detects fraudulent transactions using a Decision Tree Classifier based on features like transaction type, amount, and account balances.

Table of Contents
Introduction

Dataset

Preprocessing

Model Training

Prediction Interface

Installation

Usage

Results

Contributing

License

Introduction
This project aims to identify fraudulent transactions in financial datasets using machine learning techniques.

Dataset
The dataset, onlinefraud.csv, includes details about transactions such as type, amount, old balance, new balance, and fraud indicator. Due to its size, download it from this link.

[Download Dataset](https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection)

Preprocessing
Label Encoding: Convert categorical variables to numerical values.

Feature Selection: Use relevant features for model training.

Model Training
Using a Decision Tree Classifier, the data is split into training and testing sets for evaluation:

Data Splitting: train_test_split is used to create training and testing datasets.

Model Training: Train the classifier on the training data.

Evaluation: Assess the model's performance using accuracy metrics.

Prediction Interface
A command-line interface allows users to input transaction details and predict fraud.

Example Interaction:

Enter transaction details:
Transaction Type (CASH_OUT, PAYMENT, CASH_IN, TRANSFER, DEBIT): TRANSFER
Amount: 9000.60
Old Balance Origin: 9000.60
New Balance Origin: 0.0
The script will predict whether the transaction is fraudulent.
