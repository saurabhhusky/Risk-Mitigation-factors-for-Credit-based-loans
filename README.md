# Risk-Mitigation-factors-for-Credit-based-loans
Credit Train Dataset
This repository contains the Credit Train dataset, which consists of information about loan applications submitted to a bank. The dataset is used for analyzing loan statuses and predicting whether a loan has been fully paid or charged off.

Dataset Overview
Dataset Size: 100,514 rows and 19 columns
Target Variable: Loan Status (indicates whether a loan has been fully paid or charged off)
Predictor Variables
The dataset includes the following 13 predictor variables:

Current Loan Amount
Term
Credit Score
Annual Income
Years in current job
Home Ownership
Purpose
Monthly Debt
Years of Credit History
Number of Open Accounts
Number of Credit Problems
Bankruptcies
Tax Liens
Missing Values
The dataset contains missing values in some columns, which need to be handled before further analysis. Appropriate techniques will be applied to handle missing data.

Categorical Variable Encoding
Some variables in the dataset are categorical and need to be encoded before being used in predictive models. Encoding techniques will be applied to convert categorical variables into numerical representations.

Outlier Treatment
The dataset may have outliers that need to be treated before building models. Outlier detection and treatment techniques will be applied to ensure the quality of the dataset.

Sampling for Analysis
For the purpose of this assignment, we have taken a subset of the dataset consisting of 10,000 randomly sampled rows. This subset includes 5,000 rows from low interest loans and 5,000 rows from high interest loans. This sampling allows us to perform analysis efficiently while maintaining a representative sample.

Future Enhancements
In future iterations, we plan to leverage technologies like Pyspark to optimize our code and improve its efficiency. This will enable us to handle large volumes of data more effectively and enhance our analysis capabilities.

Please refer to the code and documentation in this repository for further details on data preprocessing, analysis, and predictive modeling using the Credit Train dataset.

