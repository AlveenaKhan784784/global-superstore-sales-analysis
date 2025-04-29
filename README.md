# Global Superstore Sales Analysis

This project presents an end-to-end analysis of the **Global Superstore** dataset, covering data preprocessing, exploratory data analysis (EDA), SQL-based insights, and a Power BI dashboard for business intelligence reporting. The objective is to uncover key sales insights, identify performance trends, and create an interactive dashboard to support data-driven business decisions.

## About the Dataset

The **Global Superstore** dataset simulates global retail operations, containing transactional sales records across regions, countries, and product categories. It includes information on:

- Order ID, Order Date, Ship Date
- Customer and Segment details
- Product Category and Sub-Category
- Sales, Quantity, Discount, and Profit
- Country and Region

This dataset is ideal for practicing data cleaning, exploratory data analysis, and visualization skills for business reporting.

### Dataset Summary:
- **Data File**: [https://www.kaggle.com/datasets/khaledramadanali22/global-superstore-dataset](superstore.csv)
- **Rows**: [51290]
- **Columns**:  [27]


## Project Objectives

- Clean and preprocess the dataset for analysis
- Perform Exploratory Data Analysis (EDA) to identify trends and patterns
- Use SQL for business-focused queries
- Build an interactive dashboard in Power BI to communicate insights clearly


## Tools & Technologies

- **Python**: Data preprocessing, EDA (`pandas`, `seaborn`, `matplotlib`)
- **SQL**: Business queries executed in Jupyter Notebook
- **Power BI**: Interactive dashboards and visual storytelling
- **Jupyter Notebook**: Combined workflow for analysis and SQL


## Data Preprocessing Highlights

- **Missing Data**: No missing values were found in the dataset.
- **Duplicates**: Duplicate records were removed to ensure accurate analysis.
- **Outliers**: Outliers were identified, but due to their relevance, they were retained for analysis.
- **Data Preprocessing: Date Handling and Feature Extraction**: Convert the 'Order.Date' column to datetime format and converted into separate columns for `Order Month` and `Order Year` and `Order Week`.


## Exploratory Data Analysis (EDA)

Explored the data to identify:

- Distribution of Sales, Profit and Quantity
- Top-selling product categories
- Profitability by Category
- Discount vs Profit


## SQL-Based Analysis

Performed SQL queries in Jupyter to answer key business questions, such as:

### Sales and Revenue Analysis:
1. What is the total revenue generated?

2. What is the total quantity of products sold?

3. Which product category has the highest sales revenue?

4. Which product is sold the most by quantity?

5. Which discount range generated the most revenue?

6. Which customers received the highest total discounts?

### Customer and Store Insights:
7. What is the average order value per customer?

8. Top 5 customers based on total spending.

9. Which store/location generated the highest revenue?

### Time-based Insights:
10. Which month had the highest sales?

11. What is the revenue trend by month?

### Inventory Analysis:
12. How many different products were sold overall?


## Power BI Dashboard Overview

The dashboard includes:

- **KPI Cards**: Total Sales, Total Profit, Total Orders
- **Bar Chart**: Sales by Category
- **Pie Chart**: Regional Sales Share
- **Line Chart**: Year-wise Sales Trend
- **Matrix**: Customer-wise Sales
- **Slicers**: Region and Category filters

All visuals are arranged in a clean layout using alignment tools and consistent formatting.

## Key Insights

- **Technology** category generated the most revenue.
- **Central** was the most profitable region.
- **2014** had the highest overall sales.
- A small group of customers contributed a major portion of sales.

## Conclusion

This project showcases the ability to clean and analyze real-world datasets, extract meaningful insights using both Python and SQL, and design a compelling Power BI dashboard. It demonstrates a full workflow from raw data to interactive reporting — essential for any data analyst or business intelligence role.

## 📬 Contact

**Alveena Khan**  
📍 Karachi, Pakistan  
🎓 BS in Mathematics | Minor in Physics and Statistics
📫 []
