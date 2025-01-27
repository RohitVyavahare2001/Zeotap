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

---

## Assignment Tasks

### Step 1: Exploratory Data Analysis (EDA)
Open and run the Jupyter notebook `FirstName_LastName_EDA.ipynb` to perform the **EDA** on the provided datasets. This notebook covers the following:

- **Overview of customer, product, and transaction data**
- **Key visualizations and insights** derived from the data

### Step 2: Lookalike Model
Open and run the Jupyter notebook `FirstName_LastName_Lookalike.ipynb` to build the **Lookalike Model**. The model identifies the **top 3 similar customers** for each of the first 20 customers based on product purchase behavior and transaction patterns.

- The output is saved in **Lookalike.csv**, which contains the recommended similar customers for the first 20 customers.

### Step 3: Customer Segmentation
Open and run the Jupyter notebook `FirstName_LastName_Clustering.ipynb` to perform **customer segmentation**. Customers are grouped based on their **total spending** and **transaction quantity**. KMeans clustering is used to form the customer segments.

---

## Key Business Insights

Following are the key business insights derived from the **EDA**:

### 1. **Customer Region Distribution**
- Customers are predominantly from specific regions, with some regions showing higher customer concentration. Marketing efforts should be targeted toward these high-density regions.

### 2. **Customer Sign-up Trends**
- A significant increase in customer sign-ups has been observed in recent years, which suggests a growing interest in the business. This trend could be linked to marketing campaigns or product expansions.

### 3. **Product Category Distribution**
- Certain product categories dominate the market, and focusing marketing and sales efforts on these categories could yield higher returns. Further analysis of these categories could guide inventory management and promotion strategies.

### 4. **Price Range Concentration**
- Most products are priced within a specific price range. Understanding this concentration allows for better pricing strategies, helping businesses stay competitive in the market while maximizing profit margins.

### 5. **Transaction Volume Growth**
- There has been consistent growth in the transaction volume, indicating that the business is expanding its operations and attracting more customers over time.

For further detailed insights, refer to the **insights.pdf**, which provides a comprehensive analysis and strategic recommendations based on the dataset.

---

## Output Files

- **`final.ipynb`**: The primary code file where **EDA**, **Lookalike Model**, and **customer segmentation** tasks are implemented.
  
- **`Lookalike.csv`**: Contains the top 3 similar customers for each of the first 20 customers. This file is generated as part of the Lookalike Model task.
  
- **`insights.pdf`**: A document where detailed business insights are drafted based on the results from the EDA and clustering analyses.

---

## Requirements

The following Python libraries are required to run the notebooks:

- **pandas**
- **matplotlib**
- **seaborn**
- **scikit-learn**


You can install the necessary dependencies using the following command:

```bash
pip install pandas matplotlib seaborn scikit-learn
