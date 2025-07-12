# Sales-Dashboard
### **Sales & Customer Analysis Dashboard**
---
### **1. Project Title**
Sales & Customer Analysis Dashboard
A dynamic, interactive data visualization tool built to explore a simulated company’s sales data, focusing on key performance indicators (KPIs), sales trends, and customer behavior across different product categories.

### **2. Short Description**
The Sales & Customer Analysis Dashboard is a visually engaging Power BI report designed to provide actionable insights into sales operations and customer dynamics. The dashboard helps users explore and analyze key metrics such as total sales, total orders, and top-performing products and customers. This tool is intended for use by sales managers, marketing strategists, and business analysts seeking to understand sales performance and identify opportunities for growth.

### **3. Tech Stack**
The dashboard was built using the following tools and technologies:
* **Power BI Desktop** – Main data visualization platform used for report creation.
* **Power Query** – Data transformation and cleaning layer for reshaping and preparing the data, including handling duplicates.
* **DAX (Data Analysis Expressions)** – Used for calculated measures (`Total Sales`, `Total Orders`, `Average Order Value`) and conditional logic.
* **Data Modeling** – A **One-to-Many relationship** was established between the `Orders` and `Details` tables to enable cross-filtering and accurate aggregation.
* **File Format** – .pbix for development and .csv for the source data.

### **4. Data Source**
**Source:** Simulated Sales Data (`Orders.csv`, `Details.csv`)
Data on sales transactions, including details on order dates, customer names, states, and product information such as quantity, category, sub-category, and sales amount.

### **5. Highlights**
**Business Problem**
In a competitive market, a business needs a clear understanding of its sales performance to make informed decisions. Raw transaction data, often stored in separate files, makes it difficult to answer critical business questions such as: What is our total revenue? Which products are selling the most? Where are our top customers located? Raw data also often contains inconsistencies like duplicate records that must be addressed for accurate reporting.

**Goal of the Dashboard**
To deliver a two-page interactive visual tool that:
* Centralizes key sales metrics and performance indicators on a single screen.
* Supports decisions related to product strategy, customer targeting, and regional sales performance.
* Provides a comprehensive overview of sales trends and customer behavior.

**Walkthrough of Key Visuals**

#### **Key Visuals (Slide 1: Sales & Order Overview)**
* **Key KPIs:** Card visuals showing Total Sales, Total Orders, Total Quantity, and Total Customers provide a quick snapshot of business health.
* **Sales Trends:** A column chart visualizes monthly sales performance, revealing trends and seasonal patterns.
* **Sales by Category:** A pie chart breaks down total sales by product category, highlighting which categories contribute most to revenue.

#### **Key Visuals (Slide 2: Customer & Regional Analysis)**
* **Top Customers by Sales:** A donut chart identifies the top customers based on total sales, which helps in targeted marketing.
* **Sales by State:** A filled map visualizes sales performance by state, helping to identify top-performing regions and potential growth areas.
* **Key Metrics:** Tables and multi-row cards display key metrics like average order value and product performance by sub-category.

**Business Impact & Insights**
* **Performance Monitoring:** The dashboard enables managers to monitor real-time sales and customer metrics at a glance.
* **Strategic Planning:** Insights into regional sales and product category performance can inform targeted marketing campaigns and inventory planning.
* **Customer Understanding:** Identifying top customers and analyzing their buying behavior can help in building stronger customer relationships and loyalty programs.

* ### 6. Screenshots
* Snapshot of Dashboard 1 ()
* Snapshot of Dashboard 2 ()
