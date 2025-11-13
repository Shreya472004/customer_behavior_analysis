#  Customer Behavior Analysis

##  Overview  
This project focuses on analyzing customer purchasing behavior using **Python**, **SQL**, and **Power BI**.  
It demonstrates an end-to-end data analytics workflow — from **data cleaning and transformation** to **insight generation** and **dashboard visualization**.

---

##  Dataset  
- **Name:** Customer Behavior Dataset  
- **Source:** (Specify if known — e.g., Synthetic / E-commerce sample data)  
- **Format:** CSV / Excel  
- **Description:**  
  Contains customer demographics, product details, purchase amount, discounts, review ratings, and subscription status.  
- **Objective:**  
  To identify key customer behavior patterns, spending trends, and segment insights to improve decision-making.

---

##  Tools & Technologies  
| Tool / Technology | Purpose |
|--------------------|----------|
| **Python (Pandas, NumPy)** | Data loading, cleaning, and preparation |
| **SQL (MySQL / SQL Server)** | Querying and performing data analysis |
| **Power BI** | Dashboard creation and visualization |
| **Excel / CSV** | Raw data source |

---

##  Project Workflow  

###  Data Cleaning & Preparation (Python)
- Loaded raw dataset using **Pandas**  
- Removed duplicates, handled missing values, and corrected data types  
- Standardized columns (e.g., gender, subscription status, shipping type)  
- Exported the cleaned dataset for SQL and Power BI use  

>  Tools used: Pandas, NumPy  

---

###  Data Analysis (SQL)
Performed analytical queries to extract insights and answer key business questions.  
Some of the major SQL queries include:

1. Total revenue by gender  
2. Discount users who spent above average  
3. Top 5 products by average review rating  
4. Comparison of purchase amounts between Standard and Express shipping  
5. Average spending and total revenue by subscription status  
6. Products with the highest percentage of discounted purchases  
7. Customer segmentation (New, Returning, Loyal)  
8. Top 3 most purchased products per category  
9. Repeat buyers and their subscription trends  
10. Revenue contribution by age group  

> 📄 SQL file: `customer_behavior sql queries.sql`

---

###  Dashboard Development (Power BI)
- Imported the cleaned dataset into **Power BI Desktop**  
- Built interactive visuals including:  
  - Gender-based revenue distribution  
  - Product and category performance  
  - Customer segmentation and loyalty analysis  
  - Subscription and discount impact on revenue  
  - Age group–wise spending trends  
- Used slicers, filters, and KPIs for interactivity and dynamic analysis  

>Power BI file: `Customer_Behaviour_Analysis.pbix`

---

## Dashboard Insights  
Some key takeaways from the project:
- Female customers contributed slightly higher total revenue  
- Subscribed users had higher average spending  
- Loyal customers (with more previous purchases) formed the top revenue segment  
- Discounts significantly influenced purchasing frequency  
- Products with strong review ratings correlated with higher sales volume  

---

## How to Run the Project  

### Step 1: Run Data Cleaning (Python)
1. Open the `.ipynb` or `.py` file (if you have one).  
2. Install dependencies:
   ```bash
   pip install pandas numpy
