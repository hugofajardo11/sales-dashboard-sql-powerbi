# 📊 Sales Analytics Dashboard (SQL + Power BI)

An interactive sales analytics dashboard built with SQL and Power BI to analyze retail transactions.  
This project transforms raw sales data into actionable insights to help businesses improve decision making in revenue forecasting, product performance, and customer segmentation.  

---

## 🚀 Project Overview
The goal of this project was to design a dashboard that answers key business questions:  
- What are the total revenue, and sales quantity? 
- Which products and regions generate the most revenue?  
- How do monthly/quarterly sales trends change over time?  
- Which customers contribute the most to overall revenue?  

---

## 🗂 Dataset
File: [db_dump.sql]("C:\Users\fajar\Downloads\db_dump.sql")  
- Contains sales transaction data with tables for:
  -customers
  -date
  -market
  -products
  -transactions

### How to Load the Data
1. Create a new MySQL database:
   ...sql
   CREATE DATABASE sales_db;

---

## 🔧 Tools & Skills
- **SQL** → data extraction, cleaning, and transformations  
- **Power BI** → data visualization & dashboard design  

---

## 📊 Dashboard Preview

![Sales Dashboard Screenshot]("C:\Users\fajar\OneDrive\Pictures\Screenshots\sales_dashboard.png")

---

## 💡 Key Insights
  -Delhi NCR dominates with 519.51M revenue (52.8% of total) and 988K sales, indicating strong market concentration
  -Revenue peaked in mid-2018 at ~40M monthly but declined significantly by 2020 to ~15M, suggesting market challenges or seasonal impact
  -Top customer concentration risk: Top 5 customers generate 413.33M+ revenue, showing heavy dependence on key accounts
  -Mumbai underperforms relative to potential with only 150.08M revenue despite being a major market
  -Product portfolio imbalance: Single product (Blank) generates 468.96M (47.6% of total revenue), indicating over-reliance on one SKU
  -Tier 2 cities show opportunity: Markets like Ahmedabad (132.31M) and Bhopal (58.61M) have growth potential compared to their current contribution
  -Consistent decline trend from 2019-2020 requires immediate strategic intervention to reverse negative trajectory

---

## 🗺 Dashboard Features
  -KPI cards (Total Revenue: 984.81M, Sales Quantity: 2M)
  -Line chart: Revenue trend analysis over time (2018-2020) showing seasonal patterns
  -Horizontal bar charts: Revenue and sales quantity breakdown by market/city
  -Top performers analysis: Top 5 products by revenue and Top 5 customers by revenue
  -Geographic market segmentation (Delhi NCR, Mumbai, Ahmedabad, etc.)
  -Time-based filtering capabilities (Year: 2017-2020, Month: January-June)
  -Comparative analysis between different markets and customer segments
  -Product performance tracking with revenue contribution metrics

---

## 🚀 How to Reproduce

Follow these steps to replicate the project locally:

### 1️⃣ Set up MySQL Database
1. Install MySQL Server (if not already installed).  
2. Open MySQL Command Line or MySQL Workbench.  
3. Create a new database for the project:
...sql
CREATE DATABASE sales_db;
---

## 📈 Business Impact
This project demonstrates the ability to:  
  -Transform raw sales data into actionable revenue insights for strategic planning
  -Design executive-level performance dashboards for data-driven decision-making
  -Identify high-performing markets and products to optimize resource allocation
  -Monitor revenue trends to detect seasonal patterns and growth opportunities
  -Enable geographic expansion strategies through market performance analysis

---

## 🧑‍💻 Author
**Hugo Fajardo** – MIS Major @ FIU, aspiring Business Analyst  
