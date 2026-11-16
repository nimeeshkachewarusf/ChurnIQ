# ChurnIQ || Customer Churn Intelligence Dashboard
Customer Churn Intelligence Dashboard using Power BI. Its an interactive Power BI dashboard built to explore customer churn, identify patterns in customer behavior, and understand how churn affects revenue.

The goal of this project was to go beyond simply showing how many customers leave. I wanted to understand which customer segments experience the highest churn and how those findings could help a business make better retention decisions.

## Dashboard Preview

### Executive Overview

![Executive Overview](screenshots/Executive%20Overview%20Screenshot.png)

### Churn Deep Dive

![Churn Deep Dive](screenshots/churn-deep-dive.png)

## Dataset

I used the **IBM Telco Customer Churn** dataset, which contains information on 7,043 customers, including their subscriptions, contract types, payment methods, tenure, monthly charges, and churn status.

**Source:** [IBM Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Tools Used

- **Power BI Desktop** – Dashboard development and interactive visualizations
- **Power Query** – Data cleaning, type conversions, and customer segmentation
- **DAX** – Measures for customer counts, churn rate, and monthly revenue associated with churned customers

## Dashboard Features

The report contains two pages:

**1. Executive Overview**

Provides a high-level view of customer churn through four KPIs: total customers, churned customers, churn rate, and monthly charges associated with churned customers.

It also includes comparisons by contract type and customer tenure, along with interactive filters for contract, internet service, and senior citizen status.

**2. Churn Deep Dive**

Explores churn across internet service types, payment methods, technical support, and other customer characteristics.

An interactive decomposition tree allows users to break down churn rates across multiple customer segments and explore combinations associated with higher churn.

Both pages include navigation buttons for easy movement between views.

## Key Findings

- **26.54% of customers churned**, representing 1,869 out of 7,043 customer records.
- **Month-to-month customers had the highest churn rate** at 42.71%, compared with 2.83% for customers on two-year contracts.
- **Newer customers were more likely to churn.** Customers with 0–12 months of tenure had a churn rate of 47.44%, compared with 9.51% for customers with 49+ months of tenure.
- **Payment method showed notable differences.** Customers using electronic checks had a churn rate of 45.29%, considerably higher than customers using other payment methods.
- **Fiber optic customers had a churn rate of 41.89%**, suggesting an area worth investigating further.

These patterns suggest that early customer retention, contract flexibility, and differences in the payment and service experience could be useful areas for further analysis.

The findings show associations within the dataset and do not establish that these factors directly cause churn.

## What I Learned

This project helped me get more comfortable with Power BI beyond basic visualizations. I worked with DAX measures, cleaned and transformed data using Power Query, and built interactive reports that respond to user selections.

One of the more interesting parts was using the decomposition tree to explore churn across different combinations of customer attributes.

I also learned how important it is to validate calculations and organize visuals so that the dashboard communicates useful information without overwhelming the user.

## Running the Dashboard

1. Download `Customer-Churn-Intelligence.pbix` from this repository.
2. Open the file using Power BI Desktop.
3. Explore the Executive Overview and Churn Deep Dive pages.
4. Use the slicers and decomposition tree to investigate churn across different customer segments.
