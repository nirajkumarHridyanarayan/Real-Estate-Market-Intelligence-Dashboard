# 🏙️ Real Estate Market Intelligence Dashboard

**End-to-End Data Analytics Project (Python + Power BI)**

---

## 📌 Project Overview

This project presents an **end-to-end real estate analytics solution** designed to solve real-world business problems faced by property developers, investors, and sales teams.

The solution covers the **entire analytics lifecycle**:

* Raw data with real-world issues
* Data cleaning & preprocessing using **Python**
* Business logic handling
* Advanced **Power BI dashboard** with interactive & smart visuals
* Insight-driven storytelling

---

## 🎯 Business Objectives

* Analyze **real estate sales performance**
* Identify **key revenue-driving factors**
* Compare **pricing trends across cities**
* Understand **sold vs available inventory**
* Enable **data-driven decision-making** for stakeholders

---

## 🧩 Dataset Description

* **Rows:** ~12,000+ property records
* **Type:** Simulated real-world dataset (business realistic)
* **Domain:** Indian real estate market

### Key Columns

* Property_ID
* City
* Locality
* Property_Type (Apartment, Villa, Studio, Builder Floor)
* Area_sqft
* Bedrooms, Bathrooms
* Furnishing
* Parking
* Property_Age
* Price
* Sale_Status
* Sale_Date

---

## ⚠️ Real-World Data Problems Included

This dataset intentionally includes **real-life data challenges**:

* ❌ Missing values (NULLs)
* ❌ Duplicate property records
* ❌ Business logic inconsistencies
* ❌ Outliers in price and property age

This makes the project **highly realistic and interview-ready**.

---

## 🧹 Data Cleaning & Preprocessing (Python)

**Tools Used:**

* Python
* Pandas
* NumPy

### Cleaning Steps Performed

* Removed duplicate records using `Property_ID`
* Handled missing values:

  * Furnishing → `Unknown`
  * Parking → `0`
  * Sale_Date → `Not Sold`
* Fixed business logic:

  * Sold properties without sale date flagged
* Treated outliers using price capping
* Converted date columns into proper datetime format
* Created derived columns for analysis

✔️ Result: **Clean, analysis-ready dataset** exported to Power BI

---

## 📊 Power BI Dashboard Overview

### Dashboard Title

> **Real Estate Market Intelligence Dashboard**

Designed with a **clean, aesthetic, and executive-friendly UI**

---

## 🔑 Key KPIs (Top Cards)

| KPI                    | Description                    |
| ---------------------- | ------------------------------ |
| Total Properties       | Total property listings        |
| Total Sales Value      | Overall revenue generated      |
| Sold Percentage        | Conversion rate                |
| Average Property Price | Mean selling price             |
| Average Price per Sqft | Pricing efficiency             |
| Sales YTD              | Year-to-date sales performance |

---

## 📈 Visual Analysis (Chart-Wise Explanation)

### 1️⃣ Sales Trend Over Time (Line Chart)

**Columns Used:**

* Axis: Year
* Values: Total Sales Value

**Insight:**
Shows year-wise market growth and demand fluctuations.

---

### 2️⃣ Average Price by City (Bar Chart)

**Columns Used:**

* City
* Average Property Price

**Insight:**
Highlights price differences across cities.

---

### 3️⃣ Price per Sqft by City (Bar Chart)

**Columns Used:**

* City
* Avg Price per Sqft

**Insight:**
Reveals true affordability beyond absolute price.

---

### 4️⃣ Average Price by Property Type (Column Chart)

**Columns Used:**

* Property_Type
* Average Price

**Insight:**
Identifies which property type commands premium pricing.

---

### 5️⃣ Price vs Area Analysis (Scatter Plot)

**Columns Used:**

* X: Sum of Area_sqft
* Y: Sum of Price
* Legend: City

**Insight:**
Validates correlation between size and pricing.

---

### 6️⃣ Sold vs Available Properties (Donut Chart)

**Columns Used:**

* Sale_Status
* Count of Property_ID

**Insight:**
Shows market demand and inventory health.

---

### 7️⃣ Decomposition Tree (Smart Visual 🔥)

**Value:**

* Sum of Bathrooms

**Explain By:**

* City → Furnishing

**Insight:**
Identifies which city and furnishing type drives higher property features.

---

### 8️⃣ Interactive Table (Matrix)

**Columns Used:**

* City
* Area_sqft
* Bathrooms
* Property_Age

**Insight:**
Detailed comparison across cities and property types.

---

## 🎛️ Interactivity & Smart Features

* Dynamic slicers:

  * City
  * Property Type
  * Locality
  * Sale Status
* Drill-down enabled visuals
* Cross-filtering across all charts
* Clean navigation & layout

---

## 🛠️ Tools & Technologies Used

* **Python** – Data Cleaning & Preparation
* **Pandas & NumPy** – Data manipulation
* **Power BI Desktop** – Data modeling & visualization
* **DAX** – Measures & KPIs
* **GitHub** – Version control & project sharing

---

## 💡 Key Business Insights

* Certain cities consistently outperform others in sales value
* Furnished properties sell faster
* Villas and Builder Floors have higher average prices
* Area alone does not guarantee higher price — location matters
* Inventory imbalance identified using sold vs available analysis

---

## 🚀 Why This Project Stands Out

✔ End-to-end analytics workflow
✔ Real-world data problems handled
✔ Business-focused insights
✔ Advanced Power BI visuals
✔ Interview-ready explanation

---

## 👤 Author

**Niraj Mourya**
Aspiring Data Analyst | Power BI | Python | SQL
