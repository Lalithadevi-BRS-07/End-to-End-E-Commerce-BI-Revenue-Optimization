# End-to-End E-Commerce Business Intelligence & Revenue Optimization

## 1. Project Overview

This project focuses on analysing e-commerce business data to identify revenue trends, customer purchasing behaviour, product performance, profitability and business growth opportunities.

The objective is to transform raw transaction data into meaningful business insights using SQL, Python, Excel and Power BI.

This project simulates a real-world business intelligence assignment performed by a Data Analyst in an e-commerce company.

**Dataset Note:** The included datasets are synthetically generated for educational and portfolio purposes. They do not represent actual company transactions or customers.

## 2. Project Objectives

- Analyse overall e-commerce sales and revenue performance.
- Identify profitable and loss-making product categories.
- Understand customer purchasing behaviour.
- Perform RFM-based customer segmentation.
- Analyse repeat purchases and customer retention.
- Evaluate the impact of discounts on profitability.
- Identify high-performing sales channels.
- Develop interactive business intelligence dashboards.
- Provide data-driven recommendations for revenue optimization.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data cleaning and exploratory data analysis |
| Pandas | Data manipulation |
| NumPy | Numerical analysis |
| Matplotlib | Data visualization |
| SQL / PostgreSQL | Database management and business queries |
| Power BI | Interactive dashboards and reporting |
| DAX | KPI calculations and business measures |
| Excel | Data inspection and validation |
| GitHub | Project documentation and version control |

## 4. Dataset Description

The project contains four relational datasets.

### Customers Dataset
- Customer ID
- Customer State
- Signup Date

### Products Dataset
- Product ID
- Product Category
- Unit Cost
- List Price

### Orders Dataset
- Order ID
- Customer ID
- Order Date
- Order Status
- Payment Type
- Delivery Days
- Acquisition Channel
- Device

### Order Items Dataset
- Order ID
- Product ID
- Quantity
- Unit Price
- Discount Rate
- Gross Sales
- Product Cost
- Shipping Revenue
- Shipping Cost

## 5. Project Architecture

The project follows an end-to-end data analytics workflow:

1. Data Collection
2. Data Cleaning
3. Data Preprocessing
4. Database Creation
5. SQL Analysis
6. Exploratory Data Analysis
7. Customer Segmentation
8. Business Intelligence Development
9. Dashboard Creation
10. Business Recommendations

## 6. SQL Analysis

SQL is used to extract meaningful business information.

Key analytical operations include:

- INNER JOIN and LEFT JOIN
- Common Table Expressions (CTEs)
- Window Functions
- GROUP BY and HAVING
- Subqueries
- Ranking Functions
- Customer Purchase Analysis
- Revenue and Profit Calculations

Business queries cover monthly revenue, product profitability, customer purchasing patterns, repeat purchase rates, discount analysis and channel performance.

## 7. Python Analysis

Python is used for data processing and exploratory analysis.

Major activities:

- Data cleaning and validation
- Missing value identification
- Duplicate record checking
- Monthly revenue analysis
- Category-wise profitability analysis
- Customer RFM segmentation
- Acquisition channel analysis
- Data visualization

Libraries used:

- Pandas
- NumPy
- Matplotlib

## 8. Customer Segmentation – RFM Analysis

RFM analysis is performed using three important metrics:

- Recency: How recently a customer purchased.
- Frequency: How frequently a customer purchased.
- Monetary: How much a customer spent.

Customers are assigned RFM scores to help identify valuable and repeat customers.

## 9. Power BI Dashboard

The Power BI dashboard is designed with five analytical pages.

### Page 1: Executive Overview
- Total Revenue
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin
- Monthly Revenue Trends

### Page 2: Product and Category Analysis
- Category-wise Revenue
- Product Profitability
- Top Performing Products
- Discount Analysis

### Page 3: Customer Intelligence
- Customer Segmentation
- Repeat Customer Rate
- Customer Purchase Behaviour
- Geographic Distribution

### Page 4: Marketing Channel Analysis
- Channel-wise Revenue
- Channel-wise Profit
- Order Distribution
- Customer Acquisition Channel Performance

### Page 5: Operations Analysis
- Delivery Performance
- Order Status
- Payment Method Distribution
- Delivery Time Analysis

## 10. Business Questions Answered

1. Which product categories generate the highest revenue?
2. Which products contribute the most profit?
3. Which customer segments generate the highest sales?
4. What is the monthly revenue growth trend?
5. Which acquisition channels perform best?
6. How do discounts influence profitability?
7. What percentage of customers make repeat purchases?
8. Which geographical regions contribute the most revenue?
9. How efficiently are customer orders delivered?
10. What business strategies can improve revenue and profitability?

## 11. How to Execute the Project

### Step 1: Extract the ZIP File

Extract the downloaded project ZIP file into your local computer.

### Step 2: Install Python Dependencies

```bash
pip install -r src/requirements.txt
```

### Step 3: Execute Python Analysis

```bash
python src/analysis.py
```

The generated reports will be stored in the reports folder.

### Step 4: Create the PostgreSQL Database

Create a database named:

```sql
CREATE DATABASE ecommerce_bi;
```

Execute the database schema available in:

`sql/01_schema.sql`

Import the four CSV files into their respective database tables.

### Step 5: Execute SQL Queries

Open the SQL file:

`sql/02_business_analysis_queries.sql`

Execute the queries using PostgreSQL or pgAdmin.

### Step 6: Develop Power BI Dashboard

1. Open Power BI Desktop.
2. Import all four CSV datasets.
3. Establish the required table relationships.
4. Create DAX measures.
5. Develop the five dashboard pages.
6. Add interactive filters and slicers.
7. Validate the dashboard totals against SQL results.

Refer to:

`powerbi/DAX_measures.txt`

## 12. Expected Project Outcomes

- Improved understanding of e-commerce sales performance.
- Identification of profitable products and categories.
- Better understanding of customer purchasing behaviour.
- Identification of customer retention opportunities.
- Insights into marketing channel performance.
- Interactive business intelligence reporting.
- Data-driven revenue optimization recommendations.

## 13. Future Enhancements

- Develop advanced sales forecasting models.
- Implement market basket analysis.
- Perform customer lifetime value analysis.
- Develop discount elasticity analysis.
- Build automated data pipelines.
- Implement advanced cohort retention analysis.
- Deploy dashboards for business reporting.

## 14. Conclusion

This project demonstrates an end-to-end data analytics workflow by integrating Python, SQL and Power BI. It transforms raw e-commerce transaction data into actionable business insights and provides analytical recommendations for improving sales performance, customer retention and profitability.


**Tools:** Python, SQL, PostgreSQL, Power BI and Excel  
**Dataset:** Synthetic E-Commerce Transaction Data  
**Author:** Your Name
