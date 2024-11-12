# Anomaly Detection in Credit Card Fraud Analysis

## Project Overview
This project aims to detect fraudulent credit card transactions to help minimize financial losses and ensure customers are only charged for legitimate transactions. Using a dataset containing both legitimate and fraudulent credit card transactions, the project leverages machine learning techniques to distinguish between normal and fraudulent behavior.

The data is pre-processed with **Principal Component Analysis (PCA)** to convert the fields into numerical values suitable for analysis. In addition, we incorporate features such as transaction amount, time differences between consecutive transactions, and fraudulent transactions per unique credit card. We utilize **Neural Networks** and **Autoencoders** to model the anomalies, enabling efficient fraud detection.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Modeling Techniques](#modeling-techniques)

## Dataset
The dataset consists of anonymized records of credit card transactions, each labeled as either legitimate or fraudulent. This dataset has been transformed using **PCA** to facilitate numerical analysis. Key features in the dataset include:
- **Transaction Amount:** The monetary value of the transaction.
- **Time Difference:** The time elapsed between consecutive transactions.
- **Fraud Label:** Indicates whether the transaction is legitimate (0) or fraudulent (1).

## Features
- **Principal Component Analysis (PCA)** is used for dimensionality reduction to enable efficient anomaly detection on transformed features.
- **Neural Networks and Autoencoders** are used together to identify patterns and anomalies.
- Each unique credit card's transaction history, including the time difference between transactions and amounts, is considered to improve model accuracy.

## Modeling Techniques
Two main approaches are used to detect fraudulent transactions:
1. **Neural Networks**: A supervised learning model trained to classify transactions as legitimate or fraudulent.
2. **Autoencoders**: An unsupervised model trained to reconstruct the data and identify outliers (fraudulent transactions) based on reconstruction errors.


