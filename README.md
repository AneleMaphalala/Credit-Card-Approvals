# **Credit-Card-Fraud-Detection**

## Introduction
Credit Card Fraud Detection involves identifying and preventing unauthorized or suspicious transactions on credit card accounts. 

## Data Description
This dataset includes transactions over two days, with 492 fraud cases out of a total of 284,807 transactions. The data is highly imbalanced, with fraudulent transactions making up only 0.172% of the total.

The dataset features only numerical inputs derived from PCA (Principal Component Analysis) transformations. Due to confidentiality, the original features and detailed background information cannot be provided. Features V1 through V28 are the PCA-derived principal components, while 'Time' and 'Amount' are the only features not transformed by PCA. 'Time' represents the number of seconds elapsed since the first transaction in the dataset, and 'Amount' is the transaction amount, which can be used for cost-sensitive learning depending on the example. The 'Class' feature indicates whether a transaction is fraudulent (1) or not (0).

Given the class imbalance, it is recommended to use the Area Under the Precision-Recall Curve (AUPRC) for evaluating accuracy, as confusion matrix accuracy may not be meaningful in this context.


## Project Journey
The journey, outlined in the comprehensive table of contents, covered various stages:

1. Importing Packages
2. Load Data
3. Exploratory Data Analysis (EDA)
4. Data Engineering
5. Modeling
6. Model Evaluation
7. Model Deployment
8. Model Deployment
9. Conclusion


## Installation
To run this project, ensure you have Python installed. Follow these steps to set up the environment:

1. **Clone the repository:**
- "git clone https://github.com/AneleMaphalala/Credit-Card-Fraud-Detection.git"
- "cd Credit-Card-Fraud-Detection"

2. **Create a virtual environment:**
- "python -m venv env"
- "source env/bin/activate  # On Windows, use `env\Scripts\activate`"

### **Summary and Impact**
