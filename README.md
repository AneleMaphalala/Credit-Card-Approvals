# **Credit-Card-Approvals**

## Introduction
A credit card is a financial tool issued by banks or financial institutions that allows the cardholder to borrow funds to make purchases, pay for services, or withdraw cash up to a certain credit limit. Credit Card Approvals is the process by which a bank or financial institution evaluates a person's credit-worthiness to decide whether or not to approve their application for a credit card.

## Data Description
The dataset comprises two main files, `Credit_card.csv` and `Credit_card_label.csv`, which together provide detailed information about credit card applicants and the outcomes of their applications. This dataset provides a comprehensive overview of the applicant's demographic, financial, and employment information, which can be used to analyze factors affecting credit card approval decisions. Below is a description of each feature in the datasets:

1. **`Credit_card.csv`**
- `Ind_ID`: Unique identifier for each client.
- `Gender`: Gender of the applicant (e.g., Male, Female).
- `Car_owner`: Indicates whether the applicant owns a car (Yes/No).
- `Propert_owner`: Indicates whether the applicant owns property (Yes/No).
- `Children`: The number of children the applicant has.
- `Annual_income`: The annual income of the applicant.
- `Type_Income`: Type of income the applicant receives (e.g., Salary, Pension, Business).
- `Education`: The highest level of education attained by the applicant (e.g., High School, Bachelor’s, Master’s).
- `Marital_status`: The marital status of the applicant (e.g., Single, Married, Divorced).
- `Housing_type`: The applicant’s living situation (e.g., Renting, Homeowner, Living with parents).
- `Birthday_count`: The applicant's age represented as the backward count of days from the current day (0 means today, -1 means yesterday, etc.).
- `Employed_days`: The number of days since the applicant started their current employment, represented as a backward count from the current day (0 means today, positive values indicate the applicant is currently unemployed).
- `Mobile_phone`: Indicates whether the applicant has a mobile phone (Yes/No).
- `Work_phone`: Indicates whether the applicant has a work phone (Yes/No).
- `Phone`: Indicates whether the applicant has any phone number (Yes/No).
- `EMAIL_ID`: Indicates whether the applicant has an email address (Yes/No).
- `Type_Occupation`: The occupation type of the applicant (e.g., Manager, Sales, Laborer).
- `Family_Members`: The size of the applicant's family, including themselves.

2. **`Credit_card_label.csv`**
- `ID`: The unique identifier (Ind_ID) used to join with the application data in the Credit_Card.csv file.
- `Label`: The outcome of the credit card application, where 0 indicates the application was approved, and 1 indicates it was rejected.

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
