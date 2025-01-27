# ZEOTAP: eCommerce Transactions Analysis

This repository contains a comprehensive data science assignment for analyzing an eCommerce transactions dataset. The assignment involves performing exploratory data analysis (EDA), building a lookalike model, and segmenting customers based on their profiles and transaction histories. The dataset consists of three main files: `Customers.csv`, `Products.csv`, and `Transactions.csv`.

## Files Overview

### 1. `Customers.csv`
This file contains information about the customers.

- `CustomerID`: Unique identifier for each customer.
- `CustomerName`: Name of the customer.
- `Region`: Continent where the customer resides.
- `SignupDate`: Date when the customer signed up.

### 2. `Products.csv`
This file contains details about the products.

- `ProductID`: Unique identifier for each product.
- `ProductName`: Name of the product.
- `Category`: Product category.
- `Price`: Product price in USD.

### 3. `Transactions.csv`
This file contains transaction details.

- `TransactionID`: Unique identifier for each transaction.
- `CustomerID`: ID of the customer who made the transaction.
- `ProductID`: ID of the product sold.
- `TransactionDate`: Date of the transaction.
- `Quantity`: Quantity of the product purchased.
- `TotalValue`: Total value of the transaction.
- `Price`: Price of the product sold.

## Assignment Tasks

### Step 1: Exploratory Data Analysis (EDA)
Open and run the Jupyter notebook FirstName_LastName_EDA.ipynb to perform EDA on the provided datasets. This notebook covers the following:
Overview of customer, product, and transaction data.
Key visualizations and insights derived from the data.
### Step 2: Lookalike Model
Open and run the Jupyter notebook FirstName_LastName_Lookalike.ipynb to build the Lookalike model.
The model recommends the top 3 similar customers for each of the first 20 customers.
The output is saved in Lookalike.csv.
### Step 3: Customer Segmentation
Open and run the Jupyter notebook FirstName_LastName_Clustering.ipynb for customer segmentation.
Customers are grouped based on their total spending and transaction quantity.
KMeans clustering is used to form the customer segments.

## Business Insights
Following are the key business insights derived from the EDA:

  ### 1.Customer Region Distribution:
  Customers are majorly from specific regions, and regions with high customer concentration should be targeted for marketing.
  
  ### 2.Customer Sign-up Trends:
  A significant increase in customer sign-ups in the past few years, indicating growing business interest.
  
  ### 3.Product Category Distribution:
  Certain product categories dominate, which suggests that focusing on these categories could yield better sales.
  
  ### 4.Price Range Concentration:
  Most products are priced within a specific range, providing valuable information for pricing strategies.
  
  ### 5.Transaction Volume Growth:
  The transaction volume has seen growth in recent years, indicating expanding business operations.



## Requirements

- pandas
- matplotlib
- seaborn
- scikit-learn
