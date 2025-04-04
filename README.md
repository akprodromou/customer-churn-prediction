# Customer Churn Prediction

## Project Overview

This project uses an IBM dataset for a fictional telco company operating in the USA, that provides home phone and Internet services to 7043 customers in California. It aims at examining client data to understand relationships (Explanatory Analysis), employing a machine learning model to predict customer churn (Prediction Modelling), and provide some business recommendations.

## Data Description

The dataset consists of customer attributes such as:

* Demographics: Age, Dependents, etc.
* Service Usage: Internet type, Contract Type, Monthly Charges.
* Engagement Metrics: Number of Referrals, Online Security.
* Churn Indicator: Whether a customer has left the service.

## Key Findings

* Monthly Charge is the strongest predictor of churn – Customers with lower monthly charges have different churn patterns.
* Age groups show varying churn trends – Seniors (55+) have the highest churn rates.
* Customers with dependents and referrals churn less – Indicating the influence of social networks and family connections.
* City occurrence in dataset correlates with churn – Certain cities have higher churn rates.

## Predictive Model Performance

A Random Forest model was selected as the predictive model, achieving:

* 83% Accuracy
* Precision (Churn = 1): 73%
* Recall (Churn = 1): 59%

## Business Recommendations

Customer Retention Strategies:
* Offer loyalty discounts or incentives for seniors to reduce churn.
* Analyze high-churn cities for local service improvements.
* Promote referral programs since customers with referrals churn less.
* As customers on longer-term contracts churn less, incentives for 1 or 2-year contracts could improve retention.

## Repository Structure

customer-churn-prediction
│── data # Folder for dataset files
│ ├── raw # Unprocessed datasets
│ └── processed # Cleaned and transformed datasets
│── notebooks # Jupyter notebooks for analysis
│ └── customer-churn-prediction-project.ipynb # Main analysis
│── reports # Reports & insights
│ └── business_recommendations.md
│── requirements.txt # Python dependencies
│── README.md # Project documentation
└── .gitignore # Files to ignore

## How to Run the Analysis

Clone the repository and install dependencies:

git clone https://github.com/YOUR_GITHUB_USERNAME/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt

Run the Jupyter notebook:

jupyter notebook notebooks/customer-churn-prediction-project.ipynb
