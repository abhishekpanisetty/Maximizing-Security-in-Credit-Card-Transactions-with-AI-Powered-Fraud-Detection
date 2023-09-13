# Maximizing-Security-in-Credit-Card-Transactions-with-AI-Powered-Fraud-Detection

# INTRODUCTION

The United States holds the unfortunate distinction of being the most susceptible country to credit card fraud globally. According to the Federal Trade Commission (FTC), instances of credit card fraud in the US surged by 44.6% from 271,927 cases in 2019 to 393,207 cases in 2020, leading to an approximate loss of $3.3 billion. Credit card fraud incidents also constituted a significant portion, accounting for 393,207 out of nearly 1.4 million (approximately 28.08%) reported cases of identity theft in 2020. In response, this report aims to develop and emphasize the efficiency of a predictive model for fraud detection.

# DATASET DESCRIPTION

- Dataset Name: Card Transaction Data
- Dataset Description: The dataset contains information regarding actual credit card transactions from a US government organization. It furnishes details about each transaction, including credit card information, merchant details, transaction date, transaction amount, and a "fraud label" column indicating the fraudulent or legitimate nature of each transaction.

- Total Fields: 10
- Total Records: 96,753
- Time Period: January 1, 2010, to December 31, 2010

# SUMMARY

We conducted a comprehensive analysis of credit card transaction fraud cases. Our approach began with an exploratory data analysis to gain insights into critical fields and understand data distribution. Subsequently, we performed data cleaning, addressed outliers, and handled missing values. Over 1000 candidate variables were generated, and we employed feature selection techniques, including filter and wrapper methods, to identify the most relevant variables.

We applied these variables in various machine learning models, including logistic regression, boosted trees, random forest, and neural networks. Our top-performing model for fraud prediction was Light Gradient Boosting, which achieved an 85% False Discovery Rate (FDR) at a 3% false positive rate for the testing dataset and a 56.4% FDR at a 3% false positive rate for the out-of-time (OOT) dataset.
