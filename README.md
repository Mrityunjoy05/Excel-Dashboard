# Streamline & Spotlight: Unraveling the Narrative of Supply Chain Excellence and Digital Footprints

### 📊 A Data-Driven Analysis of Supply Chain Operations and Digital Engagement

---

## **Project Overview**

This project, **“Streamline & Spotlight,”** was conducted under **DataCo Analysis Group**, a consultancy specializing in business analytics.
The goal was to explore how **supply chain efficiency** and **digital consumer behavior** collectively shape organizational performance.

By integrating and analyzing two large-scale datasets — **supply chain metrics** and **digital access logs** — this analysis delivers actionable insights through:

* **Sales Trend Analysis** — identifying revenue and shipment performance over time.
* **Product Popularity Index** — understanding which categories and items drive demand.
* **Peak Traffic Time Analysis** — recognizing when users are most active online to align supply and marketing strategies.

---

## 🎯 **Objectives**

* Perform extensive **data cleaning, transformation, and validation** on 80K+ raw records.
* Conduct **Sales Trend Analysis** to detect variations in performance across regions, categories, and delivery timelines.
* Build a **Product Popularity Index** using access logs and sales data to measure online and offline demand alignment.
* Analyze **Peak Traffic Time** patterns to uncover consumer activity behavior and its potential impact on sales.

---

## 📂 **Datasets Used**

### 1. **Supply Chain Dataset** (`DataCoSupplyChainDataset.csv`)

Provides insights into logistics, delivery performance, and sales.
| FIELDS | DESCRIPTION |
| --- | --- |
| Type | Type of transaction made |
| Days for shipping (real) | Actual shipping days of the purchased product |
| Days for shipment (scheduled) | Days of scheduled delivery of the purchased product |
| Benefit per order | Earnings per order placed |
| Sales per customer | Total sales per customer made per customer |
| Delivery Status | Delivery status of orders: Advance shipping, Late delivery, Shipping canceled, Shipping on time |
| Late_delivery_risk | Categorical variable that indicates if sending is late (1), it is not late (0) |
| Category Id | Product category code |
| Category Name | Description of the product category |
| Customer City | City where the customer made the purchase |
| Customer Country | Country where the customer made the purchase |
| Customer Email | Customer's email |
| Customer Fname | Customer name |
| Customer Id | Customer ID |
| Customer Lname | Customer lastname |
| Customer Password | Masked customer key |
| Customer Segment | Types of Customers: Consumer, Corporate, Home Office |
| Customer State | State to which the store where the purchase is registered belongs |
| Customer Street | Street to which the store where the purchase is registered belongs |
| Customer Zipcode | Customer Zipcode |
| Department Id | Department code of store |
| Department Name | Department name of store |
| Latitude | Latitude corresponding to location of store |
| Longitude | Longitude corresponding to location of store |
| Market | Market to where the order is delivered: Africa, Europe, LATAM, Pacific Asia, USCA |
| Order City | Destination city of the order |
| Order Country | Destination country of the order |
| Order Customer Id | Customer order code |
| order date (DateOrders) | Date on which the order is made |
| Order Id | Order code |
| Order Item Cardprod Id | Product code generated through the RFID reader |
| Order Item Discount | Order item discount value |
| Order Item Discount Rate | Order item discount percentage |
| Order Item Id | Order item code |
| Order Item Product Price | Price of products without discount |
| Order Item Profit Ratio | Order Item Profit Ratio |
| Order Item Quantity | Number of products per order |
| Sales | Value in sales |
| Order Item Total | Total amount per order |
| Order Profit Per Order | Order Profit Per Order |
| Order Region | Region of the world where the order is delivered |
| Order State | State of the region where the order is delivered |
| Order Status | Order Status: COMPLETE, PENDING, CLOSED, PENDING_PAYMENT, CANCELED, PROCESSING, SUSPECTED_FRAUD, ON_HOLD, PAYMENT_REVIEW |
| Product Card Id | Product code |
| Product Category Id | Product category code |
| Product Description | Product Description |
| Product Image | Link of visit and purchase of the product |
| Product Name | Product Name |
| Product Price | Product Price |
| Product Status | Status of the product stock: 1 = not available, 0 = available |
| Shipping date (DateOrders) | Exact date and time of shipment |
| Shipping Mode | Standard Class, First Class, Second Class, Same Day |
---

### 2. **Access Logs Dataset** (`TokenizedAccessLogs.csv`)

Captures digital engagement metrics and online user interactions.

| Field      | Description           |
| ---------- | --------------------- |
| Product    | Product name          |
| Category   | Product category      |
| Date       | Timestamp of access   |
| Month      | Month of access       |
| Hour       | Hour of access        |
| Department | Department of product |
| IP         | User IP address       |
| URL        | Accessed page URL     |

---

## ⚙️ **Methodology**

1. **Data Preprocessing**  
   Cleaned and standardized both datasets, fixed inconsistencies, removed duplicates, and created analytical features.  

2. **Exploratory Data Analysis (EDA)**  
   Examined sales, profit, delivery efficiency, and product demand patterns; merged datasets to compare online interest with actual sales.  

3. **Key Analyses Conducted**  
   Conducted sales trend analysis, measured product popularity, and identified peak traffic times to extract actionable insights.

---

## 📈 **Key Insights**

* Processed **80K+ supply chain and web records**, improving analytical efficiency by **10%**.
* Identified a **64% correlation** between online product views and actual sales performance.
* Highlighted **15% improvement opportunities** in delivery scheduling through late-shipment analysis.
* Revealed distinct **traffic peaks** aligning with sales surges — valuable for planning campaigns and fulfillment.

---

## 🔧 **Tools & Technologies**

| Tool                      | Usage                                  |
| ------------------------- | -------------------------------------- |
| **Microsoft Excel**       | Data cleaning, analysis, and reporting |
| **Power Query**           | Data transformation and integration    |
| **Pivot Tables & Charts** | Analytical visual exploration          |
| **Statistical Functions** | Correlation and trend analysis         |

---

## 📚 **Learning Outcomes**

* Integrated **multi-source datasets** for comprehensive business analysis.
* Strengthened **data cleaning, correlation, and feature engineering** skills.
* Discovered actionable insights from both **operational** and **digital** perspectives.

---


## **Conclusion**

This project bridges **supply chain performance metrics** with **digital consumer behavior analytics**, revealing how online engagement patterns, sales trends, and product popularity collectively shape operational outcomes.
The insights derived offer a foundation for **data-driven strategy optimization** across logistics, marketing, and product management functions.
