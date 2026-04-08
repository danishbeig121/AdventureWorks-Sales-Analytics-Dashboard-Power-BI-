# 📊 AdventureWorks Sales Analytics Dashboard (Power BI)

## 📌 Project Overview

This project showcases an **interactive Power BI dashboard** built using the **AdventureWorks dataset**, a widely used sample dataset representing a global bicycle manufacturing company.

The dashboard provides a **comprehensive view of sales performance, profitability, customer behavior, and product trends**, enabling stakeholders to make **data-driven decisions efficiently**.

---

## 🎯 Business Objectives

* Monitor key business KPIs: **Revenue, Profit, Orders, and Return Rate**
* Identify **top-performing products and categories**
* Analyze **monthly trends and performance vs targets**
* Understand **customer purchasing behavior**
* Detect **high return rates impacting profitability**

---

## 📊 Dashboard Overview

### 1️⃣ Executive Dashboard

A high-level summary designed for leadership and quick decision-making.

**Key Metrics:**

* 💰 Revenue: **$24.9M**
* 📈 Profit: **$10.5M**
* 📦 Orders: **25.2K**
* 🔁 Return Rate: **2.2%**

**Features:**

* Revenue trend over time
* Category-wise order distribution (Accessories, Bikes, Clothing)
* Top 10 products by revenue and return %
* Monthly KPI tracking
* Most ordered vs most returned products

---

### 2️⃣ Product Detail Dashboard

Deep dive into individual product performance (e.g., Road Tire Tube).

**Key Analysis:**

* Orders vs Target
* Revenue vs Target
* Profit vs Target

**Advanced Features:**

* 📊 Profit trend visualization
* 🎯 KPI tracking with gauge charts
* ⚙️ What-if parameter (Price Adjustment %)
* 📉 Adjusted vs Actual Profit comparison
* 📄 AI-generated insights

---

### 3️⃣ Customer & Regional Insights *(Optional Page)*

* Customer segmentation and behavior analysis
* Geographic sales distribution
* Identification of high-value regions and customers

---

## 🧰 Tools & Technologies

* **Power BI Desktop** – Data visualization & dashboard creation
* **DAX (Data Analysis Expressions)** – Calculated measures & KPIs
* **Power Query (ETL)** – Data cleaning and transformation
* **Data Modeling (Star Schema)** – Optimized performance and relationships
* **AI Visuals** – Automated insights and pattern detection

---

## 🏗️ Data Model

The project follows a **star schema model**, commonly used in data warehousing for efficient analytics. ([Microsoft Learn][2])

* **Fact Table:** Sales
* **Dimension Tables:** Customer, Product, Date, Territory

This structure enables **fast querying and scalable reporting**.

---

## 📂 Project Structure

```
📁 AdventureWorks-Sales-Dashboard
│── 📄 AdventureWorks_Report_FINAL.pbix
│── 📄 README.md
│── 📁 Screenshots
│     ├── Executive_Dashboard.png
│     ├── Product_Detail.png
│     ├── Customer_Detail.png
│     ├── Map_View.png
```

---

## ⚙️ How to Use

1. Download the `.pbix` file from this repository
2. Open it using **Power BI Desktop**
3. Navigate across report pages:

   * Executive Dashboard
   * Product Detail
   * Customer Insights
   * Map View
4. Use **filters, slicers, and drill-through** for interactive analysis

---

## 📌 Key Insights

* Accessories category drives the **highest order volume**
* Some products show **high return rates**, reducing profitability
* Revenue shows **seasonal spikes**, indicating demand patterns
* Pricing strategy adjustments can **significantly improve profit**
* Customer and regional analysis helps identify **growth opportunities**

---

## 🚀 Advanced Features

* ✅ KPI Cards & Trend Analysis
* ✅ Drill-through Navigation
* ✅ What-if Parameter (Price Simulation)
* ✅ Dynamic DAX Measures
* ✅ AI Visual Insights
* ✅ Target vs Actual Comparison

---

## 🔮 Future Enhancements

* Real-time data integration using **Azure Data Services**
* Predictive analytics & forecasting models
* Integration with **SQL/Data Warehouse**
* Deployment to **Power BI Service for sharing & collaboration**

## 👨‍💻 Author
**Beig Danish**
Data Engineer | 3+ Years Experience
- 📧 danishbeig121@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/danish-beig-4a6732386/)
