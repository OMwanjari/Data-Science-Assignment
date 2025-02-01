# Data Science Assignment: eCommerce Transactions Dataset

## Overview
This repository contains the code, reports, and deliverables for the **Data Science Assignment** focused on analyzing an eCommerce Transactions dataset. The dataset consists of three files: `Customers.csv`, `Products.csv`, and `Transactions.csv`. The assignment involves performing **Exploratory Data Analysis (EDA)**, building a **Lookalike Model**, and performing **Customer Segmentation** using clustering techniques.

---

## Dataset Description
The dataset contains the following files:
1. **Customers.csv**:
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**:
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**:
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

---

## Assignment Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Performed EDA on the provided dataset.
- Derived **5 business insights** from the analysis.
- Deliverables:
  - Jupyter Notebook/Python script for EDA: `Om_Wanjari_EDA.ipynb`
  - PDF report with business insights: `Om_Wanjari_EDA.pdf`

### Task 2: Lookalike Model
- Built a Lookalike Model that recommends 3 similar customers based on their profile and transaction history.
- Generated a `Lookalike.csv` file containing the top 3 lookalikes with similarity scores for the first 20 customers.
- Deliverables:
  - Lookalike CSV file: `Om_Wanjari_Lookalike.csv`
  - Jupyter Notebook/Python script for the model: `Om_Wanjari_Lookalike.ipynb`

### Task 3: Customer Segmentation / Clustering
- Performed customer segmentation using clustering techniques.
- Calculated clustering metrics, including the **DB Index**.
- Visualized clusters using relevant plots.
- Deliverables:
  - PDF report on clustering results: `Om_Wanjari_Clustering.pdf`
  - Jupyter Notebook/Python script for clustering: `Om_Wanjari_Clustering.ipynb`

---
