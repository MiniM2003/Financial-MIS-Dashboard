## 📊 Financial MIS Dashboard | Excel | Power BI | Power Query | DAX

A professional **Financial MIS Dashboard** built using **Microsoft Excel** and **Power BI** to analyze financial performance, revenue trends, profitability, budget variance, regional performance, and sales channels. This project demonstrates the complete Business Intelligence workflow—from raw data preparation to interactive dashboard creation.

---

## 📌 Project Overview

This project focuses on transforming raw financial transaction data into meaningful business insights through an interactive Power BI dashboard.

The dashboard helps stakeholders monitor:

* Revenue Performance
* Profitability
* Budget vs Actual
* Product Category Performance
* Regional Sales
* Department-wise Gross Profit
* Sales Channel Performance
* Monthly Revenue Trends
* Payment Method Analysis

---

## 🎯 Project Objectives

* Clean and prepare raw financial data.
* Perform data transformation using Power Query.
* Build a data model in Power BI.
* Create DAX measures for financial KPIs.
* Design an interactive Financial MIS Dashboard.
* Generate business insights and recommendations.

---

## 🛠️ Tools & Technologies

| Tool             | Purpose                     |
| ---------------- | --------------------------- |
| Microsoft Excel  | Data Cleaning & Preparation |
| Power Query      | Data Transformation         |
| Power BI Desktop | Dashboard Development       |
| DAX              | KPI Calculations            |
| GitHub           | Project Documentation       |

---

## 📂 Project Workflow

```text
Raw Dataset (Excel)
        │
        ▼
Data Cleaning (Excel)
        │
        ▼
Power Query
        │
        ▼
DAX Measures
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Insights & Recommendations
```

---

## 📁 Repository Structure

```text
Financial-MIS-Dashboard/
│
├──  Financial_Final.xlsx
│
│──  Financial_MIS_Dashboard.pbix 
│
├── README.md

```

---

## 📊 Dashboard Features

### KPI Cards

* Total Revenue
* Total Profit
* Total Net Profit
* Total Transactions
* Profit Margin
* Total Quantity Sold

---

### Interactive Filters

* Date
* Region
* Product Category
* Channel
* Payment Method
* Status

---

### Visualizations

* Revenue by Quarter
* Profit by Year
* Revenue by Category
* Budget vs Actual
* Department-wise Gross Profit
* Net Profit by Channel
* Monthly Revenue Trend
* Profit Margin by Region
* Discount vs Profit Margin
* Payment Method Performance by Region
* Revenue Treemap

---

## 📈 Key DAX Measures

```DAX
Total Revenue =
SUM(Financial_Data[Revenue])
```

```DAX
Total Profit =
SUM(Financial_Data[Profit])
```

```DAX
Total Net Profit =
SUM(Financial_Data[Net_Profit])
```

```DAX
Profit Margin % =
DIVIDE(
SUM(Financial_Data[Profit]),
SUM(Financial_Data[Revenue]),
0
)
```

```DAX
Total Transactions =
COUNTROWS(Financial_Data)
```

```DAX
Total Quantity =
SUM(Financial_Data[Quantity])
```

---

## 📌 Dashboard Insights

* Total Revenue reached **₹289.09M**, with **Q4** recording the highest quarterly revenue.
* The business achieved a **52.22% Profit Margin**, generating **₹150.97M** in Gross Profit.
* **Software** emerged as the highest revenue-generating product category.
* Actual Revenue closely aligned with the planned Budget across all quarters.
* The **Retail** sales channel delivered the highest Net Profit.
* The **South** region achieved the highest Profit Margin.
* Gross Profit remained consistently above **₹20M** across all departments.
* Revenue showed strong growth during the second half of the year.

---

## 💡 Business Recommendations

* Increase investment in the Software category to maximize revenue growth.
* Improve the Direct sales channel through targeted marketing strategies.
* Review operations in the Central region to improve profitability.
* Maintain the current budgeting strategy due to strong budget adherence.
* Replicate successful sales practices from high-performing regions.
* Optimize discount strategies to protect profit margins.
* Focus on strengthening lower-performing departments.
* Prepare additional inventory and marketing campaigns for Q4.

---

## 📸 Dashboard Preview

---

### 🚀 Skills Demonstrated

* Financial Data Analysis
* Data Cleaning
* Data Transformation
* Power Query
* Data Modeling
* DAX
* Dashboard Design
* KPI Development
* Business Intelligence
* Data Visualization
* Business Insights
* Executive Reporting

---

### 📊 Business KPIs

* Revenue
* Profit
* Net Profit
* Profit Margin
* Budget vs Actual
* Gross Profit
* Monthly Revenue
* Revenue by Category
* Revenue by Quarter
* Department Performance
* Regional Performance
* Channel Performance

---

### 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

* Cleaning and preparing business datasets.
* Transforming data using Power Query.
* Creating efficient data models.
* Writing DAX measures for financial analysis.
* Designing interactive Power BI dashboards.
* Converting raw data into actionable business insights.
* Presenting executive-level financial reports.

---


