# 🛒 Customer Shopping Behavior Analysis  
**End-to-End Data Analytics Project | Python · SQL · Power BI**

---

## 1. 📌 Project Overview

This project analyzes **customer shopping behavior** using transactional data from **3,900 purchases** across multiple product categories.  
The objective is to uncover insights into **spending patterns, customer segments, product preferences, and subscription behavior** to support **data-driven business decisions**.

The analysis mirrors real-world retail analytics scenarios where companies aim to improve **sales performance, customer engagement, and long-term loyalty**.

---

## 2. 📊 Dataset Summary

- **Total Rows:** 3,900  
- **Total Columns:** 18  

### Key Feature Groups:
- **Customer Demographics:**  
  Age, Gender, Location, Subscription Status  

- **Purchase Details:**  
  Item Purchased, Category, Purchase Amount, Season, Size, Color  

- **Shopping Behavior:**  
  Discount Applied, Promo Code Used, Previous Purchases,  
  Frequency of Purchases, Review Rating, Shipping Type  

- **Missing Data:**  
  - 37 missing values in the **Review Rating** column  

---

## 3. 🎯 Business Problem Statement

A leading retail company wants to better understand its customers’ shopping behavior in order to:

- Improve sales performance  
- Increase customer satisfaction  
- Strengthen long-term customer loyalty  

Management has observed changes in purchasing patterns across:
- Demographics  
- Product categories  
- Sales channels  

They are particularly interested in understanding how factors such as:
- Discounts  
- Reviews  
- Seasons  
- Subscription behavior  

influence **consumer decisions and repeat purchases**.

### Core Business Question:
> **How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

---

## 4. 🎯 Project Deliverables

1. **Data Preparation & Analysis (Python)**  
   - Cleaned and transformed raw transactional data  
   - Performed exploratory data analysis (EDA)

2. **Business Analysis (SQL)**  
   - Structured business queries to analyze:
     - Customer segments
     - Revenue drivers
     - Loyalty and repeat purchases

3. **Visualization & Insights (Power BI)**  
   - Built an interactive dashboard to highlight key patterns and trends  

4. **Report & Presentation**  
   - Documented findings and business recommendations  
   - Created a presentation to communicate insights to stakeholders  

5. **GitHub Repository**  
   - Organized Python scripts, SQL queries, Power BI file, and documentation  

---

## 5. 🔄 Analytical Workflow

### 5.1 Data Preparation & EDA (Python)

- Loaded transactional customer data
- Cleaned missing and inconsistent values
- Explored distributions of:
  - Purchase amounts
  - Customer demographics
  - Product categories
- Identified early patterns in:
  - Spending behavior
  - Discount usage
  - Subscription status

---

### 5.2 SQL-Based Business Analysis

SQL was used to answer **specific business-driven questions**, not just basic queries.

#### Business Questions Answered Using SQL:

1. **Revenue comparison by gender**
2. **High-spending customers who used discounts**
3. **Top 5 products by average review rating**
4. **Average purchase comparison between Standard vs Express shipping**
5. **Spending and revenue comparison between subscribed and non-subscribed customers**
6. **Products with the highest percentage of discounted purchases**
7. **Customer segmentation into New, Returning, and Loyal**
8. **Top 3 most purchased products within each category**
9. **Relationship between repeat buyers and subscription status**
10. **Revenue contribution by age group**

#### SQL Concepts Used:
- Aggregations (`SUM`, `AVG`, `COUNT`)
- `GROUP BY` analysis
- Subqueries
- `CASE` statements
- Common Table Expressions (CTEs)
- Window functions (`ROW_NUMBER`)
- Filtering and ordering for business interpretation

---

### 5.3 Visualization (Power BI)

Power BI was used to visualize analytical findings and present them in a **business-friendly format**.

- Visualized:
  - Revenue trends
  - Customer segmentation
  - Product and category performance
  - Discount and subscription behavior
- Designed visuals for **non-technical stakeholders**
- Focused on clarity and interpretability rather than visual complexity

---

## 6. 📈 Key Insights

- Spending behavior varies significantly across **demographics**
- Subscribed customers show stronger **revenue contribution**
- Discounts do not always reduce revenue; some discounted customers spend above average
- A small number of products dominate purchases within each category
- Loyal and repeat customers play a key role in long-term revenue

---

## 7. 📌 Business Recommendations

- **Boost Subscriptions**  
  Promote exclusive benefits to increase subscriber adoption  

- **Customer Loyalty Programs**  
  Reward repeat buyers to move them into the “Loyal” segment  

- **Review & Discount Policy**  
  Balance sales boosts with margin control  

- **Product Positioning**  
  Highlight top-rated and best-selling products in marketing campaigns  

- **Targeted Marketing**  
  Focus efforts on high-revenue age groups and express-shipping users  

---

## 8. ▶️ How to Use This Repository

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

### Step 2: Python Analysis
- Open the notebook in the `python/` folder
- Review data cleaning and EDA steps

### Step 3: SQL Analysis
- Open the SQL file in the `sql/` folder
- Execute queries using PostgreSQL
- Each query maps to a real business question

### Step 4: Power BI
- Open the Power BI file
- Refresh the dataset if required
- Explore insights interactively

---

## 9. 📂 Project Folder Structure

```text
customer-shopping-behavior-analysis/
│
├── Data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── Power BI/
│   └── customer_behavior_dashboard.pbix
│
├── Business Problem Document.pdf
├── Customer Shopping Behavior Analysis.pdf
├── Banking.pptx
└── README.md
```

---

## 10. 🏁 Conclusion

This project demonstrates a **realistic end-to-end customer analytics workflow**, combining:

- Python for data cleaning and exploratory analysis  
- SQL for structured, business-focused querying  
- Power BI for insight visualization and communication  

The analysis helps businesses better understand customer behavior, optimize marketing strategies, and improve customer retention through data-driven decision-making.

---

## 👤 Author

**Mohamed Sahad M**  
Master’s in Statistics  
Data Analytics | SQL | Power BI | Python  

