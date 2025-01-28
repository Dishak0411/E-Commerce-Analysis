# eCommerce Data Analysis Project

## Overview
This project analyzes eCommerce transaction data using various data science techniques including Exploratory Data Analysis (EDA), Lookalike Customer Modeling, and Customer Segmentation.

## Dataset
The analysis uses three primary datasets:
1. `Customers.csv`
   - CustomerID: Unique identifier for each customer
   - CustomerName: Name of the customer
   - Region: Continent where the customer resides
   - SignupDate: Date when the customer signed up

2. `Products.csv`
   - ProductID: Unique identifier for each product
   - ProductName: Name of the product
   - Category: Product category
   - Price: Product price in USD

3. `Transactions.csv`
   - TransactionID: Unique identifier for each transaction
   - CustomerID: ID of the customer who made the transaction
   - ProductID: ID of the product sold
   - TransactionDate: Date of the transaction
   - Quantity: Quantity of the product purchased
   - TotalValue: Total value of the transaction
   - Price: Price of the product sold

## Tasks

### 1. Exploratory Data Analysis (EDA)
- Comprehensive analysis of customer behavior, product performance, and sales trends
- Visualization of key metrics and patterns
- Business insights derived from data analysis

Key Features:
- Customer signup trends
- Regional distribution analysis
- Product category performance
- Sales trend analysis
- Top customer identification

### 2. Lookalike Customer Model
A model that recommends similar customers based on their profiles and transaction history.

Features:
- Uses both customer and product information
- Assigns similarity scores to recommendations
- Provides top 3 lookalikes for customers C0001-C0020

Output:
- `Lookalike.csv` containing customer similarity mappings
- Detailed model documentation

### 3. Customer Segmentation
Implementation of clustering techniques for customer segmentation.

Features:
- Flexible clustering algorithm (2-10 clusters)
- Davies-Bouldin Index calculation
- Cluster visualization
- Comprehensive metrics reporting

## Technology Stack
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn


## Clone the repository
```bash
git clone https://github.com/Dishak0411/E-Commerce-Analysis
```

## Results
- EDA insights in `Disha_Khandelwal_EDA.pdf`
- Lookalike recommendations in `Lookalike.csv`
- Clustering results and visualizations in `Disha_Khandelwal_Clustering.pdf`

## Project Structure
```
├── data/
│   ├── Customers.csv
│   ├── Products.csv
│   └── Transactions.csv
├── notebooks/
│   ├── Disha_Khandelwal_EDA.ipynb
│   ├── Disha_Khandelwal_Lookalike.ipynb
│   └── Disha_Khandelwal_Clustering.ipynb
├── results/
│   ├── Disha_Khandelwal_EDA.pdf
│   ├── Lookalike.csv
│   └── Disha_Khandelwal_Clustering.pdf
|   └── Top_customer.png
|   └── analysis.png
|   └── customer_clusters.png
├── README.md
```

## Contributors
Disha Khandelwal

## Contact
dishak0411@gmail.com
