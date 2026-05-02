# Customer Behaviour Analysis

## Project Overview

This project analyzes a sample customer purchase and engagement dataset to identify trends, patterns, and actionable insights that can help improve business decision-making. The analysis covers data cleaning, visualizations, business queries, and a summary of key findings.


## Tools Used

| Tool | Purpose |
|---|---|
| Python | Data cleaning and preparation |
| Excel | Charts, visualizations and dashboard |
| SQL | Business questions and queries |


## Project Structure

```
├── customer_data.csv                  # Raw dataset
├── clean_customer_data.csv            # Cleaned dataset
├── customer_cleaning.ipynb            # Python data cleaning script
├── Customer_Analytics_Dashboard.xlsx  # Excel charts and dashboard
├── business_queries.sql               # SQL business queries
├── Dashboard Screenshot.jpeg          #Screenshot for Dashboard
└── README.md                          # Project summary
```


## Steps Followed

### 1. Data Cleaning — Python
- Loaded the raw dataset and checked its shape and structure
- Checked for missing values and duplicate rows
- Converted date columns to proper datetime format
- Standardised text columns such as region, gender, loyalty tier and churn risk
- Exported the cleaned dataset as `customer_data_clean.csv`

### 2. Visualizations & Dashboard — Excel
The cleaned data was imported into Excel where the following charts were created:

- **Total Spend by Loyalty Tier** — shows revenue contribution by customer tier
- **Total Spend by Product Category** — compares revenue across all product categories
- **Churn Risk Distribution** — pie chart showing percentage of low, medium and high risk customers
- **Total Purchases vs Total Spend** — scatter plot showing the relationship between purchase frequency and total spend

All charts were brought together into a single **interactive dashboard** with slicers for Region so the data can be filtered dynamically.

### 3. Business Queries — SQL
The following business questions were answered using SQL:

- Which region has the highest average customer spend?
- What percentage of customers fall under each churn risk level?
- Which product categories are most popular among Platinum customers?
- Do customers with higher email engagement spend more?


## Key Insights

The data shows three clear insights. First, Platinum customers make up a small portion of the customer base but generate the highest total spend, meaning a small group of loyal customers is responsible for most of the revenue. Second, Electronics and Home & Garden are the top performing product categories by a large margin compared to categories like Books and Beauty, showing where customers prefer to spend their money. Third, 40% of customers fall under high churn risk which is a concern, as nearly half the customer base is at risk of not coming back, making customer retention a priority for the business.


## What the Findings Mean for the Business

Overall the data paints a clear picture of where the business stands. A small group of high spending customers is carrying most of the revenue, which means the business is heavily dependent on a few loyal customers rather than a broad customer base. On top of that, losing 40% of customers to churn would have a serious impact on future sales. The good news is that Electronics and Home & Garden are strong performing categories that customers clearly enjoy buying from, giving the business a solid foundation to build on. In simple terms, the business needs to protect its best customers, win back the ones who are leaving, and use its strongest product categories to attract new buyers.


## Recommendation

Based on the data, the company should focus on two main areas. First, since Platinum customers bring in the most revenue, the company should work on moving more customers into higher loyalty tiers by offering simple rewards like discounts or bonus points for reaching a spending target. Second, with 40% of customers being high churn risk, sending a win-back email with a small offer or discount to customers who have not purchased in a while could bring them back and increase overall sales. These two steps alone could make a noticeable difference in revenue without needing a large investment.

Note: The sample dataset used in this project was generated with the help of Claude AI. All analysis, cleaning, visualizations, and insights were performed independently.
