# Project Name: Customer Loyalty and Transaction Analysis

## Overview

This project focuses on analyzing customer loyalty and transaction data to understand and predict customer behavior. The primary goal is to create insights and models that can help businesses make data-driven decisions to enhance customer loyalty and revenue. The project uses data from historical transactions, merchant information, and user scores to achieve this goal.

## Project Description

The project involves data exploration, preprocessing, and analysis to gain valuable insights from the available datasets. It includes the following main steps:

1. **Data Exploration**: The project begins by loading and examining four datasets: historical transactions, merchant information, new merchant transactions, and user scores. This step helps us understand the data and its features.

2. **Data Merging and Cleaning**: The historical transactions and new merchant transactions datasets are merged into a single dataset since they share the same columns. User score data is also merged with transaction data to create a unified dataset.

3. **Missing Values Analysis and Handling**: The project analyzes missing values in the dataset, identifies the columns with missing values, and addresses them. Missing values are imputed for selected columns.

4. **Outlier Detection and Removal**: Outliers in the target variable (customer loyalty score) are identified and removed to ensure data quality and model accuracy.

5. **Feature Engineering**: The project creates new features from the data, such as aggregating purchase amount statistics and examining customer behavior features like the number of transactions and transaction history.

6. **Correlation Analysis**: The correlation between different features and the customer loyalty score is analyzed to understand relationships within the data.

7. **Regression Analysis**: Linear regression is used to build a predictive model for customer loyalty scores. The project evaluates the model's performance using Mean Squared Error (MSE).

## Hypothesis Testing

The project includes two hypothesis tests:

1. **Hypothesis Test 1**: To determine if there is a significant correlation between the maximum purchase amount and the customer loyalty score.

   - Null Hypothesis (H0): There is no significant correlation between the maximum purchase amount and the customer loyalty score.
   - Alternative Hypothesis (H1): There is a significant correlation between the maximum purchase amount and the customer loyalty score.

2. **Hypothesis Test 2**: To assess if the customer loyalty score differs significantly for authorized transactions.

   - Null Hypothesis (H0): The customer loyalty score does not differ significantly for authorized transactions.
   - Alternative Hypothesis (H1): The customer loyalty score differs significantly for authorized transactions.

## Conclusion

This project provides valuable insights into customer loyalty and transaction analysis. It offers data preprocessing, feature engineering, and regression analysis to predict customer loyalty scores. Hypothesis tests help identify significant correlations and differences in customer behavior. The project serves as a foundation for businesses seeking to enhance customer loyalty and make informed decisions.

For additional details and code, please refer to the Jupyter notebook in the repository.