# EDA on Retail Sales Data

## Oasis Infobyte Data Analytics Internship – Level 1 Task 1

### Project Overview

This project focuses on Exploratory Data Analysis (EDA) of retail sales data. The analysis is performed to identify sales patterns, customer behaviour, product performance, and relationships between numerical variables.

The insights obtained from the analysis can help businesses make better decisions related to marketing, inventory management, product planning, and revenue generation.

## Objective

The main objectives of this project are:

- Understand the structure and characteristics of the retail sales dataset.
- Perform descriptive statistical analysis.
- Analyze monthly and quarterly sales trends.
- Study customer demographics based on age and gender.
- Identify the best-performing products and product categories.
- Analyze revenue and quantity sold by product category.
- Examine correlations between numerical variables.
- Identify useful business insights and provide actionable recommendations.

## Dataset

The dataset used for this project is a Retail Sales Dataset containing information about customer transactions.

### Main Columns

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Analysis Performed

### 1. Dataset Inspection

The dataset was examined for:

- Number of rows and columns
- Column names
- Data types
- Missing values
- Duplicate records

### 2. Descriptive Statistics

Statistical measures such as:

- Mean
- Median
- Mode
- Standard deviation

were analyzed for numerical variables.

### 3. Sales Trend Analysis

Monthly and quarterly sales trends were analyzed using line charts to understand changes in sales over time.

### 4. Customer Demographics

Customer behaviour was analyzed using:

- Age-group distribution
- Gender distribution

### 5. Product Analysis

Product performance was studied through:

- Top-selling products
- Revenue by product category
- Quantity sold by product category

### 6. Correlation Analysis

A correlation heatmap was created to understand relationships between numerical variables such as:

- Age
- Quantity
- Price per Unit
- Total Amount

### 7. Additional Analysis

Average transaction amount across different age groups was analyzed to identify differences in customer spending behaviour.

## Key Findings

- Customer participation is distributed across different age groups, with middle-aged groups contributing a significant share of transactions.
- Female and male customers have relatively similar representation in the dataset.
- Clothing and Electronics generate high revenue among the product categories.
- Clothing has the highest quantity sold among the major product categories.
- Price per Unit has a strong positive relationship with Total Amount.
- Quantity also contributes positively to the Total Amount of a transaction.
- Younger customer groups show higher average transaction amounts compared with some older groups.

## Business Recommendations

### 1. Focus on High-Revenue Product Categories

Businesses should maintain sufficient inventory and targeted promotions for high-revenue categories such as Clothing and Electronics to maximize sales opportunities.

### 2. Use Age-Based Marketing

Marketing campaigns can be customized according to customer age groups. Higher-spending age groups can be targeted with premium products, personalized offers, and loyalty programs.

### 3. Increase Cross-Selling and Promotional Offers

Since quantity and price per unit contribute to total transaction value, businesses can use bundle offers, discounts on multiple-item purchases, and cross-selling strategies to increase the average transaction value.

## Conclusion

The Exploratory Data Analysis provides useful insights into customer demographics, product performance, sales behaviour, and transaction characteristics. The findings can support data-driven decisions in marketing, inventory planning, product promotion, and revenue optimization.

## Project Structure

```text
DataAnalytics-L1-EDARetailSales/
│
├── L1_RetailSales_EDA.ipynb
├── retail_sales_dataset.csv
└── README.md
