# Predicting shipping delays and enhancing revenue with data‑driven insights
The objective of this project is to forecast shipping delays and quantify the expected delay in days. By accurately predicting delays, the shipping company can enhance service quality for its most profitable customers by tailoring predictions and evaluations based on revenue-generating clusters. This approach aims to improve customer satisfaction and operational efficiency by minimizing delays for high-revenue segments.

The notebook covers the following:
1. Exploratory data analysis to understand the factors influencing shipping delays.
2. Identification of clusters that generate the highest revenues for the company.
3. Development of predictive models (Linear Regression and XGBoost) to forecast shipping delays and quantify expected delays in days.
4. Customization of the training and evaluation process by prioritizing the most profitable customer segments.

## Dataset
The dataset used is [DataCo SMART SUPPLY CHAIN FOR BIG DATA ANALYSIS](https://data.mendeley.com/datasets/8gx2fvg2k6/5). It is made of 50 columns giving a comprehensive evaluation of the orders, customers and items purchased.

There are numerical and categorical variables, two even time-related. Some columns are anonymized, others are uninformative, and other have high cardinality.

For our purposes, the target variable is the delta between “Days for shipping (real)” and “Days for shipment (scheduled)” columns.

---
This project has been executed using Databricks Runtime Version 13.3 LTS DBR ML cluster.

---
A PowerBI report that contains some insightful visualization to further improve the analysis is available.
