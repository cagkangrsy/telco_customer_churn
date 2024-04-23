
## Run on your PC

Clone the project

```bash
  git clone https://github.com/cagkangrsy/telco_customer_churn_feature_engineering
```

Go to project directory

```bash
  cd telco_customer_churn_feature_engineering
```

Run the notebook.

# Telco Customer Churn Prediction

This project aims to predict customer churn in a telecommunications company using machine learning techniques.

## Project Overview

This project utilizes a dataset from a fictitious telecommunications company. The Telco customer churn data provides information about 7043 customers in California who were provided with home phone and Internet services during the third quarter. The data includes details about which customers have left, stayed, or signed up for their service. It also features customer demographics, services used, and churn status. The objective of this project is to construct a predictive model capable of identifying customers who are likely to churn. This allows the company to take proactive measures to retain these customers.


## Model

The model used in this project is the CatBoost Classifier. The model parameters are optimized using Optuna framework.

## Usage

To use this project, simply clone the repository, install the necessary libraries, and run the Jupyter notebook:

```bash
git clone https://github.com/yourusername/telco-customer-churn.git
cd telco-customer-churn
pip install -r requirements.txt
jupyter notebook
```

## Dataset

* 21 Variable 7043 Observations

* Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

* Variables contain information about customer service, account, and demographics.

* Customers who left within the last month – the column is called Churn

* Demographic information about customers - gender, senior citizen, and whether they have partners and dependents

* Customer account information – how long they have been a customer, contract, payment method, paperless billing, monthly charges and total charges

* Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies

### telco-customer-churn/WA_Fn-UseC_-Telco-Customer-Churn.csv

| **Variable** | **Definition** |
| :-------- | :------- |
| **Churn :** | Whether the customer is a churn or not (Yes, No) |
| **Gender :** | Whether the customer is a female or a male (Male, Female) |
| **SeniorCitizen :** | Whether the customer is a senior citizen or not (1, 0) |
| **Partner :** | Whether the customer has a partner or not (Yes, No) ? Whether to be married |
| **Dependents  :** | Whether the customer has dependents or not (Yes, No) (Child, mother, father, grandmother) |
| **tenure :** | Number of months the customer has stayed with the company (Multiple different numeric values) |
| **Contract  :** | Indicates the customer’s current contract type (Month-to-Month, One year, Two year) |
| **PaperlessBilling :** |Whether the customer has paperless billing or not (Yes, No) |
| **PaymentMethod :** | The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit - Card (automatic)) |
| **MonthlyCharges :** | The amount charged to the customer monthly (Multiple different numeric values) |
| **TotalCharges :** | The total amount charged to the customer (Multiple different numeric values)|
| **PhoneService :** | Whether the customer has a phone service or not (Yes, No)|
| **MultipleLines :** | Whether the customer has multiple lines or not (No phone service, No, Yes)|
| **InternetService  :** | Whether the customer is subscribed to Internet service with the company (DSL, Fiber optic, No)|
| **OnlineSecurity :** |Whether the customer has online security or not (No internet service, No, Yes)|
| **OnlineBackup :** | Whether the customer has online backup or not (No internet service, No, Yes)|
| **DeviceProtection :** |Whether the customer has device protection or not (No internet service, No, Yes)|
| **TechSupport :** |Whether the customer has tech support or not (No internet service, No, Yes)|
| **StreamingTV :** | Whether the customer has streaming TV or not (No internet service, No, Yes)|
| **StreamingMovies:**| Whether the customer has streaming movies or not (No internet service, No, Yes)|

I do not have any rights on the dataset. It is available for access in:  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn
