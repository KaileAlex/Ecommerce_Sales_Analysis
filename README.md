# E-commerce Sales Analysis Using Python

## 📌 Project Overview

This project explores an e-commerce dataset containing over 100,000 records to identify patterns in sales performance, profitability, customer behaviour, and operational efficiency.

Using Python, Pandas, NumPy, and Matplotlib in Jupyter Notebook, I performed data cleaning, exploratory data analysis (EDA), and visualization to transform raw transactional data into meaningful business insights.

The goal was to understand what drives sales, compare performance across different business segments, and identify areas that may require further investigation.

**Project Type:** Data Analysis  
**Tools:** Python, Pandas, NumPy, Matplotlib, Jupyter Notebook  
**Dataset Size:** 100,000+ records before duplicate removal

## 🎯 Project Objectives

- Clean and prepare the dataset for analysis.
- Evaluate overall sales and profitability.
- Compare performance across product categories and geographical regions.
- Analyse customer segments and their contribution to revenue.
- Investigate monthly sales trends.
- Examine the relationship between discounts and profitability.
- Assess order fulfilment and delivery performance.
- Develop actionable recommendations based on the findings.

## 🗂️ Dataset Description

The dataset contains e-commerce transaction records covering 2024 and 2025. It includes information about orders, customers, products, sales, costs, profitability, payment methods, shipping, ratings, and delivery dates.

Key columns include:

| Column | Description |
|---|---|
| `Order_ID` | Unique order identifier |
| `Order_Date` | Date the order was placed |
| `Customer_ID` | Customer identifier |
| `Category` | Product category |
| `Region` | Geographical sales region |
| `Customer_Segment` | Customer classification |
| `Quantity` | Number of units ordered |
| `Unit_Price` | Price per unit |
| `Discount` | Discount applied |
| `Sales` | Sales value after discount |
| `Cost` | Product cost |
| `Profit` | Profit earned on the transaction |
| `Rating` | Customer rating |
| `Order_Status` | Current order status |
| `Delivery_Date` | Date of delivery, where recorded |

The dataset also contains subcategories, cities, payment methods, shipping methods, shipping costs, and profit margins.

**Note:** This is a synthetic dataset created for learning and portfolio development. Its findings should not be interpreted as real-world company performance.

## 🧹 Data Cleaning and Preparation

Before conducting the main analysis, I examined the dataset's structure and data quality.

The preparation process included:

- Inspecting column data types and summary statistics.
- Identifying missing values and measuring their distribution.
- Detecting and removing exact duplicate records.
- Converting order and delivery dates into appropriate datetime formats.
- Reviewing numerical variables for unusual or potentially invalid values.
- Handling missing categorical information where appropriate.
- Evaluating the treatment of missing customer ratings.

Missing values were not automatically treated as errors. Their handling depended on the relevant column and the intended analysis.

## 📊 Exploratory Data Analysis

### 1. Overall Sales and Profitability

Evaluated key performance indicators, including:

- Total sales revenue.
- Total profit.
- Overall profit margin.
- Number of unique orders.
- Number of unique customers.
- Average order value.

These metrics provide a high-level understanding of the dataset's commercial performance.

### 2. Product Category Analysis

Compared product categories based on sales, profit, and order volume.

This analysis helps identify high-performing categories and distinguish between products that generate substantial revenue and those that contribute more effectively to profitability.

### 3. Regional Performance

Examined sales and profit across geographical regions to identify areas with stronger commercial performance and regions that may benefit from further investigation.

### 4. Customer Segment Analysis

Compared customer segments based on sales, profit, and order volume to understand how different customer groups contribute to overall performance.

### 5. Monthly Sales Trends

Aggregated sales and profit by month and used line charts to examine changes over time.

This helps identify periods of stronger or weaker sales and provides a starting point for investigating seasonal patterns.

### 6. Discount and Profitability Analysis

Grouped transactions into discount ranges and compared their associated sales, profit, and profit margins.

The objective was to investigate whether higher discounts were associated with differences in profitability, while recognising that an observed relationship does not necessarily establish causation.

### 7. Order Fulfilment and Delivery Analysis

Examined order statuses and calculated delivery durations where valid dates were available.

This analysis provides a basis for investigating cancellations, returns, pending orders, and potential delivery delays.

## 💡 Key Findings

The analysis produced the following preliminary findings from the synthetic dataset:

- **Product performance
