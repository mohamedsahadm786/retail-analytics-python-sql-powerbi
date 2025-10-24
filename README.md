# 🛒 Customer Shopping Behavior Analysis

## 📘 Project Overview
A data-driven project focused on understanding **customer shopping behavior** for a retail company aiming to improve sales, satisfaction, and loyalty.  
Using **Python**, **SQL**, and **Power BI**, this project explores purchasing patterns, identifies key drivers of customer decisions, and provides actionable insights for business strategy.

---

## 🎯 Business Problem
The retail management team observed significant shifts in:
- Purchase patterns across **demographics, categories, and channels (online vs. offline)**.  
- The impact of **discounts, reviews, and seasons** on consumer choices.  

**Objective:**  
> “How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?”

---

## 🧩 Tech Stack
- **Python:** Data Cleaning, Feature Engineering, Data Transformation  
- **PostgreSQL (SQL):** Exploratory and Business Analysis  
- **Power BI:** Interactive Visualization & Dashboard  
- **Pandas, NumPy, Matplotlib, Seaborn:** Data wrangling and visualization libraries

---

## 🧠 Data Summary
- **Rows:** 3,900  **Columns:** 18  
- **Key Features:**  
  - Customer demographics → *Age, Gender, Location, Subscription Status*  
  - Purchase details → *Item, Category, Purchase Amount, Season, Size, Color*  
  - Shopping behavior → *Discounts, Promo Codes, Reviews, Frequency, Shipping Type*  
- **Missing Data:** 37 missing values in `Review Rating` (handled via imputation)

---

## 🔧 Data Preparation & Feature Engineering (Python)
Performed in **Python** using Pandas and NumPy:
- Imported and explored data with `.info()` and `.describe()`.
- **Cleaned** missing values → imputed `Review Rating` using median per category.  
- **Renamed** columns to `snake_case` for consistency.  
- **Created new features:**
  - `age_group` (binned age values)  
  - `purchase_frequency_days` (interval between purchases)  
- **Removed redundancy:** Dropped `promo_code_used` due to overlap with `discount_applied`.  
- **Integrated with SQL:** Loaded the cleaned dataset into PostgreSQL for deeper querying.

---

## 📊 SQL-Based Business Analysis
Structured SQL queries were developed to uncover key insights:

| # | Business Question | Insight |
|---|-------------------|---------|
| 1 | Revenue by Gender | Compared total revenue by male vs. female customers |
| 2 | High-Spending Discount Users | Identified customers who use discounts but spend above average |
| 3 | Top 5 Products by Rating | Highlighted best-rated items |
| 4 | Shipping Type Comparison | Compared purchase amounts for Standard vs. Express |
| 5 | Subscribers vs. Non-Subscribers | Analyzed revenue & spend differences |
| 6 | Discount-Dependent Products | Found items most influenced by discounts |
| 7 | Customer Segmentation | Classified customers as *New, Returning, or Loyal* |
| 8 | Top 3 Products per Category | Determined best sellers by category |
| 9 | Repeat Buyers & Subscriptions | Checked correlation between >5 purchases and subscription likelihood |
| 10 | Revenue by Age Group | Measured contribution of each age group |

---

## 📈 Power BI Dashboard
An **interactive Power BI dashboard** was developed to visualize:
- Revenue trends by gender and age group  
- Subscription impact on revenue  
- Product category performance  
- Discount vs. margin trade-off  
- Loyal customer segments and repeat purchase patterns

---

## 💡 Key Business Recommendations
1. **Boost Subscriptions:** Offer exclusive benefits and targeted campaigns.  
2. **Reward Loyalty:** Design incentive programs for repeat buyers.  
3. **Optimize Discount Policy:** Balance discounts with profitability.  
4. **Product Positioning:** Promote top-rated and frequently purchased items.  
5. **Targeted Marketing:** Focus on high-revenue age segments and express-shipping users.

---

## 🗂️ Repository Structure
```
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── raw_data.csv
│
├── notebooks/
│   └── data_cleaning_feature_engineering.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── reports/
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
└── README.md
```

---

## 🚀 Key Takeaways
- Combined **Python**, **SQL**, and **Power BI** for full-stack analytics.  
- Translated raw data into **actionable business intelligence**.  
- Delivered a project that demonstrates strong **data storytelling**, **business acumen**, and **technical proficiency**.

---

**⭐ Author:** [Your Name]  
**📧 Contact:** [your.email@example.com]  
**🔗 Connect:** [LinkedIn Profile] · [Portfolio] · [GitHub Profile]
