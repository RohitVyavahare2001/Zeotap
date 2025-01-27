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

### Task 1: Exploratory Data Analysis (EDA) and Business Insights

- **Objective**: Perform an exploratory data analysis on the provided dataset and derive actionable business insights.
- **Deliverables**: 
  - A Jupyter Notebook/Python script with the EDA code.
  - A PDF report containing business insights.

**Business Insights**:
- Insight 1: Major regions of customer origin.
- Insight 2: Trends in customer signups.
- Insight 3: Dominant product categories.
- Insight 4: Product pricing distribution.
- Insight 5: Transaction trends over the years.

### Task 2: Lookalike Model

- **Objective**: Build a lookalike model that takes a user's information and recommends 3 similar customers based on their profile and transaction history.
- **Approach**: 
  - Use both customer and product information.
  - Assign a similarity score to each recommended customer.
- **Deliverables**:
  - A CSV file named `Lookalike.csv` containing the top 3 lookalike customers with their similarity scores for customers `C0001 - C0020`.
  - A Jupyter Notebook/Python script explaining the model development.

### Task 3: Customer Segmentation / Clustering

- **Objective**: Perform customer segmentation using clustering techniques based on customer profiles and transaction information.
- **Approach**:
  - Apply KMeans clustering or any other appropriate algorithm.
  - Evaluate clustering performance using the DB Index.
  - Visualize the clusters.



## Requirements

- pandas
- matplotlib
- seaborn
- scikit-learn
