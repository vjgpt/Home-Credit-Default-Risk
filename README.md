# Home-Credit-Default-Risk

## Introduction
Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.

While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.

## Dataset
Find out the dataset here :

https://www.kaggle.com/c/home-credit-default-risk/data
## Installation
- Download this repository in a zip file by clicking on this link or execute this from the terminal:

```git clone https://github.com/vjgpt/Home-Credit-Default-Risk.git```
- Download [Jupyter Notebook](http://jupyter.org/)
- Open the home_credit.ipynb file using Jupyter and start playing.

## Dependencies

- NumPy
- IPython
- Pandas
- SciKit-Learn
- Matplotlib
- Seaborn
- Garbage Collector( gc )

## Table of Content

- 1. Introduction
- 2. Importing requires packages
- 3. Retrieving the Data
- 4. Exploration of Application Train/Test Data.
  - 4.1 Merge both train and test dataset
  - 4.2 Removing Anamolies / Outlier
  - 4.3 Categorical Variables
  - 4.4 Label Encoder and One Hot Encoding
  - 4.5 Add some feature variables
- 5. Exploration of Bureau and Bureau_data
  - 5.1 One Hot Encoding
  - 5.2 Feature Engineering - Bureau Data
- 6. Exploration of Previous Application
  - 6.1 Handling Outliers
  - 6.2 One Hot Encoding
  - 6.3 Feature Engineering - Previous Application
- 7. Exploration of POS Cash Balance
  - 7.1 One Hot Encoding
  - 7.2 Feature Engineering - POS Cash Balance
- 8. Exploration of Installment Payments
  - 8.1 One Hot Encoding
  - 8.2 Adding some new features
  - 8.3 Feature Engineering - Installment Payments
- 9. Exploration of Credit Card
  - 9.1 One Hot Encoding
  - 9.2 Feature Engineering - Credit Card
- 10. LightGBM
  - 10.1 Prepare Final Train and Test data
  - 10.2 Cross Validation Model
  - 10.3 Fitting the model and Predicting
  - 10.5 Submission
