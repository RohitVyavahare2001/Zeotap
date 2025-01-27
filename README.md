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

### 1. **Customer Base Growth and Distribution**
- The platform has 200 customers across four regions. There has been a **38.6% year-over-year growth in customer acquisition** from 57 sign-ups in 2023 to 79 in 2024, reflecting strong market penetration and effective customer acquisition strategies.
- **Customer Retention**: On average, each customer generates 5 transactions, suggesting high engagement and retention.

### 2. **Revenue Performance and Order Values**
- The platform has generated a total revenue of **$689,995.56** from **1,000 transactions**, with an **average order value of $690**. This indicates a premium positioning or a successful upselling strategy.
- The transaction volume is healthy, with each customer making multiple purchases.

### 3. **Product Portfolio Balance**
- The product catalog is well-balanced across categories:
  - **Books**: 26%
  - **Electronics**: 26%
  - **Clothing**: 25%
  - **Home Decor**: 23%
- Product prices range from **$16.08 to $497.76**, with an average price of **$267.55**, catering to various price points and maintaining healthy margins.

### 4. **Customer Segmentation Opportunities**
- Three distinct customer segments were identified based on spending patterns and purchase frequency. This segmentation allows for **targeted marketing** and **personalized customer experiences**.
- **Differentiated Engagement**: Each segment requires tailored engagement strategies, including personalized product recommendations.

### 5. **Regional Market Performance**
- Customer distribution across regions (North America, South America, Asia, and Europe) reveals opportunities for regional market penetration.
- Each region exhibits **different purchasing patterns** and **category preferences**, highlighting the need for **region-specific marketing strategies** and **product assortments**.

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
