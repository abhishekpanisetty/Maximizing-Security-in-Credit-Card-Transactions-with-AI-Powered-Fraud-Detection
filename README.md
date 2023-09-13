# Credit-Card-Transaction-Fraud-Detection-Supervised-Learning-Imbalanced-Dataset

# INTRODUCTION

This Project was from my one of the classes from USC Marshall School of Business, DSO 562 - Fraud Analytics. Credit card fraud is a burden for organizations across the globe. United States is the most credit card fraud prone country in the world. According to Federal Trade Commission’s (FTC), instances of credit card fraud in the US increased by 44.6% from 271,927 in 2019 to 393,207 in 2020 which resulted in a loss of approximately 3.3 billion dollars. Credit card fraud also accounted for 393,207 of the nearly 1.4 million (~28.08%) reports of identity thefts in 2020. Through this report, our goal was to build and highlight efficient model to predict fraud.

# DATASET DESCRIPTION

Dataset Name- Card Transaction Data
Dataset Description – Dataset contains information on the actual credit card purchases from a US government organization. It provides information on Credit Card, Merchant, Date, and Amount involved in each transaction. Moreover, it also contains a column called fraud label which tells us whether the transaction is fraudulent or not.

Total Fields – 10
 ,Total Records – 96,753
 ,Time Period - 1st January 2006 – 31st December 2006
 
 
 # SUMMARY
 
A comprehensive analysis of credit card transaction fraud cases was performed. First, we performed exploratory data analysis to explore important fields and understand the distribution of the data. This was followed by data cleaning, outlier removals and missing value imputation. Then, over 1000 candidate variables were created and feature selection was performed (filter and wrapper methods) to pick the best variables. The variables were used across several models: logistic regression, boosted trees, random forest, and neural networks. Our best model to predict fraud was Gradient boosting which resulted in an 81.4% FDR at 3% for the testing dataset and a 56.4% FDR at 3% for the OOT dataset.

# REPOSITORY DESCRIPTION

The repository containts the Credit Card Transaction Dataset, the indvidual python notebooks with different processes and the final project report which gives an insight into the data quality report along with the whole process covered in this project.
