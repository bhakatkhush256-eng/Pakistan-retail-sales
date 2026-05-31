# 🛍️ Lahore Retail Sales 

> An end-to-end Excel data analysis project simulating a real Pakistani retail business across 5 major cities — built to demonstrate professional-grade spreadsheet skills for a data analyst portfolio.

---
![image alt](https://github.com/bhakatkhush256-eng/Pakistan-retail-sales/blob/78a819aa91618572fe4c6021885424a05d40b9dd/Screenshot%202026-05-31%20022044.png)






## 📌 Project Overview

This project analyzes **200 sales transactions** from a fictional retail chain operating across **Lahore, Karachi, Islamabad, Faisalabad, and Rawalpindi** during Q1 2025 (January – March). It covers 5 product categories including Clothing, Electronics, Groceries, Furniture, and Cosmetics.

The goal was to transform raw transactional data into meaningful business insights using Excel functions, Pivot Tables, and summary dashboards.

---

## 🎯 Business Questions Answered

- Which **city** generated the highest revenue in Q1?
- Which **product category** is the most profitable?
- How did **monthly revenue** trend across January, February, and March?
- Which **salesperson** performed best?
- What is the overall **profit margin** across the business?

---

## 🗂️ File Structure

```
Lahore_Retail_Sales_Q1_2025.xlsx
│
├── Sales_Data          →  200 rows of raw transactional data
├── Summary             →  SUMIF-powered revenue & profit summaries by city, category, and month
└── Practice_Functions  →  Excel function reference and practice sheet
```

---

## 🔧 Excel Skills Demonstrated

| Skill | Usage in Project |
|-------|-----------------|
| `SUMIF` | Total revenue by city and by category |
| `SUMIFS` | Multi-condition revenue (e.g. Karachi + Clothing) |
| `COUNTIF` | Count of orders per category |
| `AVERAGEIF` | Average profit per product category |
| `VLOOKUP` | Product unit price lookup |
| `IF` | Classify profit tier as High or Low |
| `MAX / MIN / AVERAGE` | Overall sales statistics |
| Pivot Tables | Cross-tabulated sales analysis |
| Conditional Formatting | Visual highlights on key metrics |
| Auto Filter | Slicing data by city, month, salesperson |

---

## 📊 Dataset Details

| Column | Description |
|--------|-------------|
| `Order_ID` | Unique identifier (ORD-1001 onwards) |
| `Date` | Transaction date (Jan – Mar 2025) |
| `Month` | January / February / March |
| `City` | Lahore, Karachi, Islamabad, Faisalabad, Rawalpindi |
| `Category` | Clothing, Electronics, Groceries, Furniture, Cosmetics |
| `Product` | 25 unique products (e.g. Shalwar Kameez, Laptop, Basmati Rice) |
| `Salesperson` | 10 sales team members |
| `Quantity` | Units sold per transaction |
| `Unit_Price_PKR` | Price per unit in Pakistani Rupees |
| `Discount_%` | Applied discount: 0%, 5%, 10%, 15%, or 20% |
| `Revenue_PKR` | Formula: Qty × Price × (1 − Discount%) |
| `Cost_PKR` | Calculated from margin rate |
| `Profit_PKR` | Revenue minus Cost |

---

## 💡 Key Insights

- **Electronics** contributed the highest total revenue due to high unit prices
- **Lahore** led all cities in total order volume across Q1
- **March** showed the strongest revenue month, indicating end-of-quarter buying patterns
- An average discount of ~10% across all orders had a measurable impact on overall profit margins

---

## 🛠️ Tools Used

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

---

## 📁 How to Use

1. Download `Lahore_Retail_Sales_Q1_2025.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Start on the **Sales_Data** sheet to explore raw data
4. Visit the **Summary** sheet to see calculated insights
5. Use the **Practice_Functions** sheet to review or test Excel formulas

---

## 👩‍💻 About

**Khushbakhat** — BSIT Student at Government College University, Faisalabad  
Aspiring Data Analyst | Excel · SQL · Power BI · Python

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/bhakatkhush256-eng)

---

*This project is part of my data analyst portfolio. The dataset is fictional and created for educational and portfolio purposes.*

