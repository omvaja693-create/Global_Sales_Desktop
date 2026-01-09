# 📊 Global Sales Data Dashboard

![Power BI](https://img.shields.io/badge/Data_Visualization-Power_BI-yellow) 
![Data Modeling](https://img.shields.io/badge/Data_Modeling-Star_Schema-blue)
![DAX](https://img.shields.io/badge/Analysis-DAX-orange)

## 🌟 Project Overview
Welcome to the **Global Sales Data Dashboard**! This project is a high-performance analytical tool built to help stakeholders track business health across the globe. By turning raw sales data into interactive visuals, this dashboard identifies growth trends, monitors profitability, and uncovers customer behavior patterns.

---

## 📸 Dashboard Preview
> **Note:** Below are the visual representations of the dashboard.

### 📈 Executive Summary View
![Dashboard Screenshot 1](INSERT_LINK_TO_IMAGE_1_HERE)
*Figure 1: High-level KPIs and Geographic distribution.*

### 🔍 Deep Dive Analysis
![Dashboard Screenshot 2](INSERT_LINK_TO_IMAGE_2_HERE)
*Figure 2: Product performance and Shipping logistics analysis.*

---

## 🚀 Key Features
* **🎯 KPI Tracking:** Real-time visibility into **Total Sales**, **Total Profit**, and **Order Volume**.
* **🌍 Geographic Insights:** Interactive map visuals to explore sales density by country and region.
* **📅 Time Intelligence:** Year-over-Year (YoY) growth and seasonal trend analysis.
* **📦 Product & Category Analytics:** Breakdown of top-performing products and sub-categories.
* **🚚 Logistics Optimization:** Analysis of shipping costs and delivery timelines.
* **⚡ Dynamic Filtering:** Slicers for Year, Segment, and Region for a personalized data experience.

---

## 🛠️ Technical Stack & Data Model
This project utilizes a **Star Schema** to ensure fast report performance and scalable data management.

* **Fact Table:** Sales Transactions (Revenue, Profit, Quantity, Discounts).
* **Dimension Tables:** * 📅 **Calendar:** Custom Date table for Time Intelligence.
    * 👥 **Customers:** Segmented by Consumer, Corporate, and Home Office.
    * 🗺️ **Geography:** Regional hierarchy (Country, State, City).
    * 🍎 **Products:** Detailed categorization.

### 🧠 Advanced DAX Measures
Some of the complex calculations used include:
* **YoY Sales Growth:** `(Current Sales - Previous Year Sales) / Previous Year Sales`
* **Profit Margin %:** `SUM(Profit) / SUM(Sales)`
* **Moving Averages:** To smooth out seasonal fluctuations in sales trends.

---

## 📂 How to View the Project
1. Clone this repository to your local machine.
2. Ensure you have **Microsoft Power BI Desktop** installed.
3. Open the file: `Global sales data dash baord.pbix`.
4. Interact with the filters to explore the data!

---

## 👤 Author
**Om Vaja** *Data Analyst & Coding Enthusiast* 📍 Focused on Data Modeling, Python, and AI/ML.

---
⭐ *If you find this project helpful, feel free to star the repository!*
