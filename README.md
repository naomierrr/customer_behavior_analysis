# 🛍️ Customer Shopping Behavior Analysis  
### End-to-End Data Analytics Project (Python • PostgreSQL • Power BI)

<div align="center">

📊 Turning Retail Data into Strategic Business Decisions  

</div>

---

## 📌 Executive Summary

This project delivers a comprehensive analysis of customer shopping behavior using a dataset of 3,900 retail transactions.

By combining **Python for data cleaning**, **PostgreSQL for advanced querying**, and **Power BI for interactive dashboards**, the project uncovers revenue drivers, customer segmentation insights, and high-impact subscription conversion opportunities.

The goal: **drive retail growth and recurring subscription revenue using data-driven strategies.**

---

## 📂 Dataset Overview

- **Source:** Customer Shopping Behavior Dataset  
- **Size:** 3,900 rows × 18 features  

### 🔑 Key Variables
- **Demographics:** Age, Gender  
- **Purchase Details:** Category, Purchase Amount, Season  
- **Behavioral Metrics:** Subscription Status, Review Rating  

---

## 🛠️ Tools & Technologies

| Layer | Tool |
|-------|------|
| 🧹 Data Cleaning & EDA | Python (Pandas, NumPy, Matplotlib) |
| 🗄️ Database | PostgreSQL |
| 📊 Visualization | Power BI |
| 📄 Reporting | Microsoft Word (PDF Report) |
| 🎤 Presentation | Gamma AI |

---

## 🔎 Project Workflow

### 1️⃣ Data Cleaning (Python)
- Handled **37 missing values** in `review_rating` using median imputation.
- Standardized column names to `snake_case`.
- Verified data integrity before database ingestion.

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed spending patterns by age group and gender.
- Identified high-performing product categories.
- Evaluated distribution of review ratings.

---

### 3️⃣ Database Integration (PostgreSQL)
- Imported cleaned dataset into PostgreSQL.
- Performed structured segmentation queries.
- Executed joins and aggregations for KPI analysis.

---

### 4️⃣ SQL-Based KPI Analysis

- 💰 Revenue by Gender:
  - **Males:** $157,890  
  - **Females:** $75,191  

- 🔁 Identified **958 high-potential repeat buyers** (non-subscribers).
- 📊 Calculated Average Purchase Amount: **$59.76**
- ⭐ Average Review Rating: **3.75**

---

### 5️⃣ Dashboard Development (Power BI)

The interactive dashboard includes:

- 📌 KPI Cards (Total Customers, Avg Spend, Avg Rating)
- 👥 Demographic Revenue Breakdown
- 📊 Category & Age Group Sales Analysis
- 🔄 Subscription Split (27% Subscribers vs 73% Non-Subscribers)

---

## 📈 Key Insights

- 👤 **Young Adults generate the highest revenue ($62,143).**
- 🔁 **958 repeat buyers represent a strong subscription conversion opportunity.**
- 🧤 Top-rated products include Gloves and Sandals.
- 🛒 Clothing category performs strongly during weekends.
- 📊 Males contribute more than 2x revenue compared to Females.

---

## 💼 Business Recommendations

- 🎯 Target repeat buyers with subscription discounts.
- 📦 Increase inventory for top-rated products.
- 📣 Launch weekend-specific marketing campaigns.
- 📊 Develop loyalty strategies for high-spend segments.

---

## 🚀 How to Run the Project

### 1️⃣ Python
Run:
```bash
Customer_Shopping_Behavior_Analysis.ipynb
```
to clean and prepare the raw dataset.

### 2️⃣ PostgreSQL
- Import cleaned CSV
- Execute:
```sql
customer_behavior_sql_queries.sql
```

### 3️⃣ Power BI
Open:
```
customer_behavior_dashboard.pbix
```
(Requires Power BI Desktop)

### 4️⃣ Documentation
Review:
```
Analysis_Report.pdf
```
for a detailed business summary.

---

## 📊 Project Architecture

```
Raw CSV
   ↓
Python Cleaning & EDA
   ↓
PostgreSQL Analysis
   ↓
Power BI Dashboard
   ↓
Business Insights & Report
```

---

## 🙏 Acknowledgments

Special thanks to **Amlan Mohanty** for the tutorial guidance that inspired the project structure and analytical approach.

---

<div align="center">

⭐ If you found this project valuable, consider giving it a star!

</div>
