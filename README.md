# RFM Analysis - README

<p align="center">
<img src="https://github.com/pjowsianka/RFM-Analysis/assets/130370888/aee99eb7-0d72-4af9-b775-011633b0c3df"  width="656" height="402" />
</p>

## Description

RFM analysis is a tool used for segmenting customers based on their buying behaviors. RFM stands for three crucial factors:
- Recency: how recently a customer made a purchase
- Frequency: how often a customer makes a purchase
- Monetary: how much money a customer spends

## Analysis Objective

The objective of this RFM analysis was to identify and group customers based on their purchasing behaviors, enabling the development of personalized marketing strategies.

## Data

The analysis utilized a sales dataset containing information about customers, their purchases, and transaction values. The dataset included:
- Customer IDs
- Transaction dates
- Purchase values

## Methodology

1. **Generating RFM Scores:**
    - Assigned RFM values to each customer.
    - Recency was calculated based on the date of the last transaction.
    - Frequency was determined by the number of a customer's transactions.
    - Monetary was calculated by the sum of a customer's purchase values.
2. **Customer Segmentation:**
    - Using machine learning, customers were divided into clusters based on their RFM scores.
    - These clusters were visualized in tables and 3D plots for better decision-making.


## Instructions for Further Action

Now that the RFM analysis and cluster identification are completed, it's time to strategize and utilize the insights obtained from the segmented customer data:

- **Development and Implementation of Personalized Marketing Strategies:**
  - Craft specific marketing strategies tailored to each identified customer group. This includes strategies for VIP customers, aiming to enhance their loyalty and encourage higher spending, as well as strategies for "Hibernating" (inactive or dormant) customers, aiming to reactivate their engagement.  
- **Refining Strategies Based on Cluster Characteristics:**
  - Continuously refine these strategies based on the distinct characteristics identified within each cluster.
- **Monitoring and Adapting:**
  - Observe customer responses and adapt marketing actions based on the performance of each cluster. 
