#  Power BI Project 
### This project is a **Sales and Customer Analysis Dashboard** built in **Power BI** using Shopify sales data. It provides insights into revenue, product performance, customer behavior, and payment methods, helping businesses make data-driven decisions.

## Repository Contents
- Shopify_Report.pbit : Power BI template file containing data model, measures, report layout, and parameters. 
- Shopify Sales.xlsx : Base dataset (orders, customers, product, billing attributes, price metrics).
- Shopify : Data Terminology.docx : Field definitions / business glossary for all key columns. Helpful when mapping Shopify exports to the model.
- assets/ : Screenshots of report pages for README preview
- README.md : You are here. Full project documentation. 

##  Project Overview

The primary objective is to:
- Evaluate **sales performance** through KPIs like revenue, total quantity, and average order value.
- Understand **customer purchase behavior** and loyalty trends (single vs repeat customers).
- Analyze **product types, payment gateways, and regions** to identify high-performing areas.
- Present insights through an **interactive dashboard with slicers, drill-through features, and dynamic measure selectors**.

##  **Business Requirements**

The dashboard was designed to address the following business questions:
1. **Transactions Performance**  
   - **Net Sales** (sum of subtotal price)
   - **Total Quantity Sold**
   - **Net Average Order Value (AOV)** = Avg of subtotal price

2. **Customer Purchase Behavior**
   - **Total Customers** (unique buyers)
   - **Single Order Customers** vs **Repeat Customers**
   - **Customer Loyalty & Repeat Rate**

3. **Retention & Value KPIs**
   - **Lifetime Value (LTV)** = Net Sales ÷ Total Customers
   - **Repeat Rate** = Repeat Customers ÷ Total Customers
   - **Purchase Frequency** = Total Distinct Orders ÷ Total Customers

4. **Product & Payment Analysis**
   - Identify top-performing **product types**.
   - Analyze **payment gateway usage** and customer preferences.

##  **Key Visuals & Features**

### **1. Regional Overview**
- **Filled Map** (Province-Level):  
  Displays province-wise performance with **color saturation** based on selected KPIs.
- **Bubble Map** (City-Level):  
  Shows **customer/sales density** with tooltips for Net Sales, Quantity, Total Customers, and Repeat Customers.
- **Bar Chart**:  
  Highlights top-performing cities, sorted dynamically by the selected KPI.

### **2. Sales Trend Over Time**
- **Daily Trend (Area Chart)**:  
  Visualizes daily Net Sales or Repeat Customers.
- **Hourly Trend (Bar/Line Chart)**:  
  Shows customer activity by hour (0–23 hrs) to identify peak activity times.

### **3. Product & Gateway Analysis**
- Bar charts to determine **best-selling product types**.
- Pie/donut charts for **payment method distribution** (Stripe, PayPal, etc.).

### **4. Detailed Data View**
- A **dedicated drill-through page** for transaction-level data.
- Allows users to explore individual **orders, customers, or products**.
---
##  **Steps Followed**

The project followed these structured steps:
1. **Requirement Gathering & Business Understanding**
2. **Data Walkthrough** – Understanding fields using the terminology document.
3. **Data Connection** – Connecting Excel data to Power BI.
4. **Data Cleaning & Quality Check**
5. **Data Modeling** – Creating relationships and star schema.
6. **DAX Calculations** – KPIs, measures, and calculated columns.
7. **Dashboard Layout** – Visual design and formatting.
8. **Chart Development** – Interactive bar, line, area, and map visuals.
9. **Report Development** – Creating drill-through and detailed views.
10. **Insights Generation** – Key findings and trends.

---
##  **Key KPIs Implemented**
- **Net Sales**  
- **Total Quantity Sold**  
- **Average Order Value (AOV)**  
- **Total Customers (Unique Buyers)**  
- **Repeat Rate**  
- **Lifetime Value (LTV)**  
- **Purchase Frequency**

---
## ⚙ **Tools & Skills Used**
- **Power BI Desktop** (Data Modeling, DAX, Visual Design)
- **Excel** for data pre-processing
- **Map Visualizations & Dynamic KPI selectors**
- **Drill-through & interactive filters**

---

##  **Dashboard Preview**
> *(![Dashboard Preview](https://github.com/Saptarshi-Poddar/Power-BI-Project/blob/main/Shopify%20Dashboard%20(1).png))*
> *(![Dashboard Preview](https://github.com/Saptarshi-Poddar/Power-BI-Project/blob/main/Shopify%20Dashboard%20(2).png))*
---
