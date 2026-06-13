# Customer Churn Analysis

## Project Overview

This project analyzes customer behavior to identify factors that lead to customer churn. The objective is to predict whether a customer is likely to leave based on activity and work order history.

---

## Problem Statement

Analyze customer data to identify patterns behind customer churn. Evaluate customer activity and behavioral trends to determine key factors leading to churn and suggest improvements for customer retention.

---

## Dataset Features

| Feature                              | Description                               |
| ------------------------------------ | ----------------------------------------- |
| Number_of_days_since_last_work_order | Number of inactive days                   |
| Number_of_work_orders_last_6_months  | Total work orders in previous 6 months    |
| Customer_Churn                       | Target variable (1 = Churn, 0 = Retained) |

---

## Hunch and Validation

### Feature 1:

Number of days since last work order

Hunch:
Longer inactivity increases churn.

Actual:
Correct

### Feature 2:

Number of work orders in last 6 months

Hunch:
More work orders reduce churn.

Actual:
Correct

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Google Colab
* GitHub

---

## Model Used

Logistic Regression

---

## Prediction Output

Example:

Predicted:
[1, 0, 1, 0]

Accuracy:
1.0

---

## Findings

* Customers with higher inactivity showed greater churn.
* Customers with more work orders had lower churn.
* Customer engagement improved retention.
* Activity level strongly influenced customer behavior.

---

## Suggestions

* Send reminder notifications.
* Improve customer engagement.
* Offer retention campaigns.
* Monitor inactive customers.

---

## Conclusion

Customer churn analysis identified that inactivity and reduced engagement increase customer churn probability. Customers with recent work orders and higher engagement demonstrated stronger retention. Predictive analysis helps businesses take early actions to reduce churn.

---

## Project Structure

customer-churn-analysis

├── customer_churn.csv

├── Customer_Churn_Analysis.ipynb

├── README.md

---

## Author

Customer Churn Analysis Project
