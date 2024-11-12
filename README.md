## Introduction

This project explores and analyzes customer churn data to uncover underlying patterns and factors that lead to customer attrition. Customer churn refers to the rate at which customers stop doing business with a company. Understanding and predicting customer churn is crucial for businesses as it significantly impacts profitability. Research shows that acquiring a new customer can be anywhere from five to 25 times more expensive than retaining an existing one (Gallo, 2014). Furthermore, a study by Frederick Reichheld of Bain & Company reveals that increasing customer retention rates by 5% increases profits by 25% to 95%, underscoring the substantial impact of effective retention strategies (Gallo, 2014).

## Objectives

The primary goals of this project are to:

- **Identify Key Factors**: Determine the demographic and service-related factors that significantly impact customer churn.
- **Predictive Modeling**: Employ logistic regression and random forests to forecast potential churn effectively, enabling proactive retention strategies.
- **Data-Driven Insights**: Provide actionable insights that businesses can use to enhance customer engagement and reduce churn rates.

These objectives aim to equip businesses with better tools to improve their customer retention strategies, thereby enhancing their overall profitability.

## Dataset Description

The dataset used in this project includes several features that may influence customer churn in the banking sector. Here is an overview of each feature:

- **RowNumber**: The record number, irrelevant to the output.
- **CustomerId**: Random values, irrelevant to the output.
- **Surname**: Irrelevant to the customer's decision to leave.
- **CreditScore**: Higher scores may indicate lower likelihood of churn.
- **Geography**: Customer location, which could influence churn.
- **Gender**: To explore if gender affects churn.
- **Age**: Older customers are generally more loyal.
- **Tenure**: Length of the customer's relationship with the bank.
- **Balance**: Higher balances may correspond to lower churn.
- **NumOfProducts**: Number of bank products the customer uses.
- **HasCrCard**: Indicates if a customer has a credit card.
- **IsActiveMember**: Active customers are less likely to churn.
- **EstimatedSalary**: Higher salaries may correlate with lower churn.
- **Exited**: Indicates whether the customer has left the bank.
- **Complain**: Whether the customer has registered a complaint.
- **Satisfaction Score**: Reflects customer satisfaction with complaint resolution.
- **Card Type**: Type of card held by the customer.
- **Points Earned**: Points a customer has earned by using their credit card.

This dataset can be accessed and downloaded on [Kaggle](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn).


### References

- Gallo, A. (2014). The Value of Keeping the Right Customers. Harvard Business Review. Retrieved from [https://hbr.org/2014/10/the-value-of-keeping-the-right-customers](https://hbr.org/2014/10/the-value-of-keeping-the-right-customers).

