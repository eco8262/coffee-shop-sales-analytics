# Coffee Shop Sales Analytics | Power BI

An interactive Power BI project focused on understanding sales performance, product trends, store performance, and customer purchasing patterns.

The goal of this project is to turn transactional data into practical business insights that can support decisions around sales performance, promotions, product focus, and customer activity.

## Dashboard

**Power BI Report:**
[View Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmU5ZDFhMWYtNzY3Yy00NTVkLTlhNDItNGQ4YjUyZGRhNTRjIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

---

## Business Questions

This analysis was designed to answer questions such as:

* How are sales changing over time?
* Which stores generate the strongest sales performance?
* Which product categories contribute the most?
* When are customers most active?
* Which products are underperforming?
* Are there relationships between transaction quantity and price?
* Where could promotions or targeted offers improve performance?

---

## Key Findings

### Sales Performance

Sales performance varied throughout the six-month period.

* **March, May, and June** were the strongest months.
* **January, February, and April** showed comparatively weaker performance.
* **Astoria and Hell's Kitchen** were the strongest-performing stores.
* Coffee generated the highest sales among the major product categories, followed by Tea and Bakery.

### Customer & Transaction Patterns

The analysis also identified several useful purchasing patterns:

* Sales activity was highest **before 10 AM**.
* Some previously underperforming products showed improvement in June.
* Transaction quantity showed a positive relationship with unit price.

These findings can help inform decisions around promotions, product bundles, and strategies for increasing sales during slower periods.

---

## Analytical Approach

The dashboard combines several types of analysis:

**Time Analysis**

* Monthly sales trends
* Transaction and quantity trends
* Month-over-month comparisons
* Sales versus monthly average

**Product Analysis**

* Category performance
* Individual product performance
* Top and bottom performing products
* Product performance versus average

**Store Analysis**

* Store-level sales comparison
* Location-based performance analysis

**Customer & Transaction Analysis**

* Sales by day and time
* Peak purchasing periods
* Transaction quantity analysis
* Price versus quantity relationship

---

## Data Model

The report is built using a **star schema** to keep the model structured and efficient.

### Fact Table

`FACT_Transaction`

Contains transaction-level information including:

* Date
* Product ID
* Store ID
* Quantity
* Sales
* Unit Price

### Dimension Tables

`DIM_Product`

* Product ID
* Product Name
* Category

`DIM_Store`

* Store ID
* Store Name
* Location

`Calendar`

* Date
* Month
* Quarter
* Year

---

## Tools

* **Power BI Desktop**
* **DAX**
* **Power Query (M)**

---

## Data

The project uses a synthetic transactional dataset covering a six-month period in 2023.

The dataset is intended for educational and portfolio purposes and does not contain real or confidential business information.

---

## Project Structure

```text
01-Coffee-Shop-Sales/
│
├── README.md
├── pbip/
├── Images/
└── Data/
```

## What This Project Demonstrates

* Data modelling with a star schema
* Power Query data preparation
* DAX-based analysis
* Time-series analysis
* KPI and dashboard development
* Product and store performance analysis
* Customer behaviour analysis
* Translating transactional data into business insights
