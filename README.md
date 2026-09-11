# 🚚 Supply Chain Analytics Dashboard

A dynamic **Power BI dashboard** designed to analyze procurement, supplier performance, quality, logistics, and delivery operations.

The **Supply Chain Analytics Dashboard** provides a 3-page interactive view of procurement spend, supplier risk, delivery performance, and logistics costs. It helps stakeholders identify cost variances, supplier issues, delivery delays, and carrier performance gaps.

## 🚀 Live Dashboard

🔗 **[View Live Supply Chain Analytics Dashboard](https://app.powerbi.com/reportEmbed?reportId=730cb13d-2d63-4a32-bf23-6365d9b6ef19&autoAuth=true&ctid=56c1d497-700b-49cf-8f8d-3dd6b20d522f)**
---
## 🛠️ Tech Stack

- 📊 **Power BI Desktop** – Dashboard development and visualization
- 📂 **Power Query** – Data cleaning and transformation
- 🧠 **DAX** – KPIs and business calculations
- 🔗 **Data Modeling** – Relationships between procurement, supplier, category, date, and logistics data
- 📁 **File Format** – `.pbix` for the Power BI project

## 📂 Data Source

The dashboard uses operational **supply chain data** covering:

- Purchase orders and PO lines
- Supplier information
- Product/category data
- Shipment records
- Carrier information
- Warehouse/logistics data
- Monthly procurement targets

### 💼 Business Problem

Supply chain data is often distributed across procurement, supplier, shipment, and logistics records, making it difficult to quickly identify cost overruns, supplier risks, quality issues, and delivery delays.

### 🎯 Goal of the Dashboard

To provide a single analytical view that helps users:

- Monitor procurement spend vs target
- Evaluate supplier performance
- Identify pricing variance
- Track quality and rejection rates
- Measure on-time delivery
- Compare carrier performance against SLA
- Analyze freight costs and transport modes

## 📊 Dashboard Pages

### 1. Overview
Provides an executive-level view of overall supply chain performance — procurement spend, purchase orders, supplier risk, quality, and delivery performance.


[![Overview](./img/overview.png)](./img/overview.png)

**Key visuals:**
- Actual Procurement Spend, Total Purchase Orders, Rejection Rate, On-Time Delivery %, and Average Lead Time KPIs
- Actual vs Target Procurement Spend
- Purchase Order Status
- Supplier Risk Level
- Spend Variance by Product Category
- Delivery Delay Analysis

### 2. Supplier & Procurement Performance
Analyzes supplier performance, procurement pricing, quality, and delivery effectiveness.

[![Supplier & Procurement Performance](./images/supplier_procurement_performance.png)](./images/supplier_procurement_performance.png)

**Key visuals:**
- Total Suppliers, Average Supplier Rating, Purchase Price Variance %, Average Quality Score, and Average Delivery Score KPIs
- Supplier & Procurement Performance analysis
- Purchase Price Variance by Supplier
- Monthly Purchase Price Variance trend
- Supplier performance detail table
- Actual Procurement Spend by Supplier

### 3. Logistics & Delivery Performance
Analyzes transportation costs, carrier performance, transit time, and delivery reliability.

[![Logistics & Delivery Performance](./images/logistics_delivery_performance.png)](./images/logistics_delivery_performance.png)

**Key visuals:**
- Total Freight Cost, Average Transit Time, On-Time Delivery %, Delayed Shipments, and Delivery SLA Gap KPIs
- Freight Cost by Transport Mode
- On-Time Delivery % by Region
- Freight Cost vs Transit Time
- Monthly On-Time Delivery trend
- Average Transit Time by Carrier
- Carrier On-Time Delivery % vs SLA Target

## 💡 Business Impact & Insights

- 💰 **Cost Control:** Identify procurement spend and pricing variances.
- 🏭 **Supplier Management:** Compare supplier quality, delivery, pricing, and risk.
- 🚚 **Delivery Optimization:** Identify delayed shipments and underperforming carriers.
- 📦 **Quality Improvement:** Monitor rejected quantities and rejection rates.
- 📈 **Better Decisions:** Provide management with a centralized view of supply chain performance.


