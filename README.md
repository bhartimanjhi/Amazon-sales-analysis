# Amazon Sales Dashboard – Excel+Power BI Project

Created an interactive Amazon Sales Dashboard using Power BI to analyze 20K+ records. It highlights ₹10.57M total revenue, top-selling categories, courier performance, fulfillment insights, and state-wise sales trends. Used Excel for data cleaning and Power BI for data modeling, DAX, and visualization to deliver clear e-commerce insights.

## Project Overview

The dashboard provides a unified view of essential e-commerce KPIs to support data-driven decisions. It highlights overall sales performance, top product categories, courier status distribution, fulfillment analysis, and state-wise demand trends.

---

## Key Insights

* Total Revenue: ₹10.57M
* Top Categories: T-Shirt, Shirt, Blazer, Wallet, Perfume, Shoes, Socks, etc.
* Courier Status: Shipped, On the Way, Unshipped, Cancelled
* Fulfillment Analysis: Amazon Fulfilled vs Merchant Fulfilled
* Delivery Partners: Ekart vs Easy Ship
* State-wise Sales Contribution: Maharashtra, Karnataka, Telangana, Uttar Pradesh, Tamil Nadu, and others
* Size-wise Distribution: XS to XXL

---

## ETL Process (Kaggle → Power BI)

### 1. Extract

* Downloaded the Amazon Sales Dataset from Kaggle
* Imported the raw Excel/CSV file into the workflow

### 2. Transform

Performed data cleaning using Excel and Power Query, including:

* Removing duplicates and invalid entries
* Standardizing column names
* Handling missing values
* Data type corrections
* Creating calculated columns
* Structuring data for analysis

### 3. Load

* Loaded the cleaned dataset into Power BI Desktop
* Built a data model using relationships and DAX calculations

---

## Tools & Technologies

* Power BI – Data modeling, DAX, and visualization
* Microsoft Excel – Data cleaning and preparation
* Power Query – ETL and transformation
* Kaggle – Data source

---

## Dashboard Features

* Professional and clean UI
* Dynamic slicers and filters
* KPIs for quick insights
* Courier and fulfillment performance analysis
* Product category and size distribution
* State-wise sales breakdown
* Interactive and easy-to-navigate layout

---

## Project Structure

```
├── Dataset/
│   └── Amazon-Sales-Report-Kaggle.xlsx
├── PowerBI/
│   └── Amazon-Sales-Dashboard.pbix
└── README.md
```

---

## Key Learnings

* Implementing the ETL process using Excel and Power Query
* Creating DAX measures for meaningful KPIs
* Building analytical dashboards in Power BI
* Data storytelling using visualizations
* Understanding key e-commerce business metrics
