# Bank Marketing Campaign Analysis

## Project Overview

This project analyzes bank marketing campaign data to understand customer behavior and identify factors associated with term-deposit subscriptions.

The main goal is to use data analysis to better understand customer segments, campaign performance, and factors related to higher subscription rates.

The dataset was obtained from Kaggle and provided as a CSV file.

## Business Question

**How can the bank improve customer targeting and campaign prioritization based on patterns found in previous marketing campaigns?**

## Tools

* Power BI
* Power Query
* DAX
* CSV

## Dashboard

The dashboard is divided into three main sections:

### 1. Campaign Overview

This page provides an overview of the campaign using key performance indicators and customer-level analysis.

It includes:

* Total Customers
* Subscribed Customers
* Non-Subscribed Customers
* Conversion Rate
* Average Balance
* Subscription Distribution
* Conversion Rate by Job
* Housing and Personal Loan Analysis

### 2. Customer Segmentation

This section focuses on understanding which customer characteristics and previous campaign outcomes are associated with higher subscription rates.

The analysis includes:

* Contact Method
* Previous Campaign Outcome
* Education
* Housing Loan
* Personal Loan
* Customer Segmentation

### 3. Campaign Strategy

This section focuses on campaign-related factors and how they relate to conversion.

It includes:

* Conversion Rate by Number of Contact Attempts
* Monthly Conversion Rate
* Customers by Month
* Customer Segment Performance
* Campaign Recommendations

## Key Findings

The analysis identified several patterns in the dataset:

* Customers with a successful outcome from a previous campaign showed a substantially higher observed subscription rate.
* Customers without housing and personal loans showed higher observed subscription rates compared with customers holding both types of loans.
* Conversion rates generally decreased as the number of campaign contact attempts increased.
* Different customer groups showed noticeable differences in subscription rates, highlighting the value of customer segmentation.
* Contact method and previous campaign outcome were also associated with differences in observed conversion rates.

> These findings describe patterns and associations in the dataset and should not be interpreted as proof of causation.

## Recommendations

Based on the observed patterns, the analysis suggests several practical actions:

* Prioritize customers with a successful previous campaign outcome when planning future campaigns.
* Use customer characteristics as part of a broader customer-prioritization strategy rather than treating all customers equally.
* Review repeated-contact strategies, especially for customers who do not respond after multiple attempts.
* Use customer segmentation to allocate campaign resources toward customers with higher observed conversion rates.
* Continue monitoring campaign performance by customer segment and contact strategy to improve future targeting.

## Customer Prioritization

A rule-based customer segmentation approach was created to classify customers into different potential groups based on patterns identified during the analysis.

The segments are intended to support campaign prioritization rather than predict customer behavior with a machine-learning model.

The segmentation can be used to distinguish between:

* **High Potential** — higher campaign priority
* **Medium Potential** — secondary campaign priority
* **Low Potential** — lower campaign priority

## Data Preparation

The dataset was prepared using Power Query before building the dashboard.

The preparation process included:

* Reviewing column data types
* Handling categorical values
* Creating calculated fields for analysis
* Creating a month number to ensure chronological month sorting
* Creating campaign-contact groups
* Preparing fields used for customer segmentation

## Project Outcome

This project goes beyond displaying descriptive statistics by connecting customer characteristics and campaign patterns to practical recommendations.

The final dashboard provides a structured view of:

**Campaign Performance → Customer Patterns → Segmentation → Recommendations**

The goal is to help transform campaign data into information that can support better customer prioritization and campaign strategy.

## Project Files

* `Bank_Marketing_Dashboard.pbix` — Power BI dashboard
* `bank.csv` — Dataset used for the analysis
* `screenshots/` — Dashboard screenshots

## Note

This project was created as a data analysis portfolio project to demonstrate skills in Power BI, Power Query, DAX, data visualization, and business-oriented analysis.
