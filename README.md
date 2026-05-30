# Telco Customer Churn Analysis

## Project Overview

This project analyzes customer churn in a telecommunications company using Python and Power BI. The objective is to identify the key factors influencing customer churn and provide actionable business recommendations to improve customer retention.

---

## Objectives

* Analyze customer churn behavior.
* Identify factors contributing to customer attrition.
* Visualize customer trends using Power BI.
* Generate business insights and recommendations.
* Build an interactive dashboard for decision-making.

---

## Dataset Information

The dataset contains customer information such as:

* Customer ID
* Gender
* Senior Citizen Status
* Partner and Dependents
* Tenure
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn Status

---

## Tools and Technologies Used

### Python

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

### Power BI

* Data Modeling
* DAX Measures
* Interactive Visualizations
* KPI Cards
* Slicers and Filters

---

## Data Cleaning Process

The following preprocessing steps were performed:

* Checked data types and column information.
* Handled missing values.
* Converted Total Charges to numeric format.
* Replaced blank values where required.
* Checked for duplicate records.
* Converted Senior Citizen values into readable categories.

---

## Key Performance Indicators (KPIs)

| KPI                     | Value        |
| ----------------------- | ------------ |
| Total Customers         | 4,000        |
| Churned Customers       | 2,000        |
| Churn Rate              | 44.35%       |
| Revenue Lost            | 119.84K      |
| Average Monthly Charges | 69.65        |
| Average Tenure          | 18.59 Months |

---

## Dashboard Insights

### Contract Type

* Month-to-Month customers show the highest churn behavior.
* Long-term contract customers demonstrate better retention.

### Payment Method

* Electronic Check users exhibit the highest churn rate.
* Customers using Credit Cards and Bank Transfers show lower churn.

### Customer Tenure

* Customers with shorter tenure are more likely to churn.
* Customer loyalty increases with tenure.

### Internet Service

* Fiber Optic customers show higher churn compared to DSL users.

### Senior Citizens

* Senior customers display a higher tendency to churn and may require targeted retention strategies.

---

## Business Recommendations

* Promote long-term contracts through discounts and loyalty programs.
* Encourage customers to switch to automated payment methods.
* Improve onboarding and engagement for new customers.
* Enhance customer support for Fiber Optic users.
* Develop personalized retention programs for senior citizens.


---

## Project Files

* `Telco_Churn_Analysis.ipynb` – Data Cleaning and Exploratory Data Analysis
* `Telco_Churn_Dashboard.pbix` – Power BI Dashboard
* `Dashboard_Screenshot.png` – Dashboard Preview
* `Telco_Churn_Report.pdf` – Detailed Project Report

---

## Conclusion

This project demonstrates how data analytics and visualization can be used to understand customer behavior, identify churn patterns, and support data-driven business decisions. The insights generated can help improve customer retention and reduce revenue loss.
