# 🏠 TATA CLiQ Home — E-Commerce Business Intelligence Dashboard

Interactive Power BI e-commerce analytics dashboard analyzing 541,909 transaction records across 8,082 customers, 375 products, and multiple countries to generate actionable sales, retention, and product performance insights.

 

> **Disclaimer:** This is an independent portfolio/business intelligence case study built on a public online-retail dataset. It is **not** an official internal report of Tata CLiQ or the Tata Group; branding is used solely for presentation purposes.


## 📑 Table of Contents

- [📊 Project Overview](#-project-overview)
- [🎯 Business Problem](#-business-problem)
- [🎯 Project Objectives](#-project-objectives)
- [📁 Dataset](#-dataset)
  - [Dataset Columns](#dataset-columns)
  - [Geographic Coverage](#geographic-coverage)
  - [Product Categories](#product-categories)
- [🔍 Data Quality Assessment](#-data-quality-assessment)
  - [Data Quality Results](#data-quality-results)
- [📈 Key Dataset KPIs](#-key-dataset-kpis)
- [📊 Dashboard Design](#-dashboard-design)
  - [🏠 Home Page](#1--home-page)
  - [📈 Dashboard 1 — Sales & Geographic Analysis](#2--dashboard-1--sales--geographic-analysis)
  - [🛒 Dashboard 2 — Product Performance](#3--dashboard-2--product-performance)
  - [👥 Dashboard 3 — Customer & Retention Analysis](#4--dashboard-3--customer--retention-analysis)
- [🎛️ Dashboard Interactivity](#-dashboard-interactivity)
  - [Year](#year)
  - [Country](#country)
  - [Month](#month)
- [📅 Monthly Sales & Revenue Analysis](#-monthly-sales--revenue-analysis)
- [🌍 Geographic Revenue Analysis](#-geographic-revenue-analysis)
- [🛒 Product Performance Analysis](#-product-performance-analysis)
- [👥 Customer Retention Analysis](#-customer-retention-analysis)
- [🔁 Repeat Purchasing by Category](#-repeat-purchasing-by-category)
- [💡 Key Business Insights](#-key-business-insights)
  - [1. Retention Is the Biggest Growth Opportunity](#1-retention-is-the-biggest-growth-opportunity)
  - [2. The Business Is Highly Seasonal](#2-the-business-is-highly-seasonal)
  - [3. The UK Is the Core Market](#3-the-uk-is-the-core-market)
  - [4. Functional Home Products Perform Strongly](#4-functional-home-products-perform-strongly)
- [🚀 Business Recommendations](#-business-recommendations)
  - [1. Build a Customer Retention & Loyalty Program](#1-build-a-customer-retention--loyalty-program)
  - [2. Prepare Aggressively for the September–December Peak](#2-prepare-aggressively-for-the-septemberdecember-peak)
  - [3. Increase Basket Size Through Cross-Selling & Selective Expansion](#3-increase-basket-size-through-cross-selling--selective-expansion)
- [🛠️ Tools & Technologies](#-tools--technologies)
- [🔄 Project Workflow](#-project-workflow)
- [📂 Repository Structure](#-repository-structure)
- [📄 Project Report](#-project-report)
- [📌 Key Takeaways](#-key-takeaways)
- [🎓 Portfolio Value](#-portfolio-value)
- [👨‍💻 Author](#-author)

---

## 📊 Project Overview

This project presents an interactive **TATA CLiQ Home E-Commerce Business Intelligence Dashboard** developed to analyze sales performance, customer retention, product performance, and geographic revenue distribution for an online home-retail business.

The project transforms a raw e-commerce transaction dataset containing **541,909 transaction lines** into an interactive business intelligence solution designed to help management understand revenue drivers, seasonal demand patterns, top-performing products, and customer loyalty behavior.

The dashboard provides both a **high-level executive view** and detailed drill-down analysis using interactive filters for:

* Year
* Country
* Month

The project combines **data cleaning, KPI development, segmentation, visualization, and business storytelling** to demonstrate an end-to-end data analytics workflow.

> **Disclaimer:** This is an independent portfolio/business intelligence case study built on a public online-retail dataset. It is **not** an official internal report of Tata CLiQ or the Tata Group; branding is used solely for presentation purposes.

---

## 🎯 Business Problem

E-commerce businesses generate large volumes of transaction data. Without an analytical dashboard, management may find it difficult to quickly answer questions such as:

* How many customers and orders does the business have?
* What is the total revenue, and how is it trending month over month?
* Which months and seasons generate the most revenue?
* Which countries contribute the most revenue?
* Which products and categories are the top performers — by revenue and by units sold?
* How many customers are repeat buyers, and how much revenue do they generate?
* Which product categories drive the most repeat purchases?
* Where should the business focus retention, inventory, and expansion efforts?

This project addresses these questions through an interactive Power BI dashboard.

---

## 🎯 Project Objectives

The main objectives of the project were to:

1. Analyze overall sales performance (customers, orders, revenue).
2. Identify monthly and seasonal revenue trends.
3. Analyze revenue distribution by country.
4. Identify top-performing products by revenue and by units sold.
5. Calculate the repeat customer rate and its revenue contribution.
6. Analyze monthwise repeat customer behavior.
7. Identify top repeating product categories and products.
8. Build interactive KPIs and visualizations.
9. Enable dynamic filtering by year, country, and month.
10. Convert raw transaction data into actionable business insights.

---

# 📁 Dataset

The dataset contains:

**541,909 transaction records**

covering order details, customer identifiers, product/SKU information, invoice dates, and country of purchase.

### Dataset Columns

| Column | Description |
|---|---|
| Invoice No. | Unique order/invoice identifier |
| StockCode | Unique product/SKU code |
| Description | Product name |
| Product Category | Product category classification |
| Quantity | Units purchased |
| Invoice Date | Date and time of transaction |
| Unit Price | Price per unit |
| Customer ID | Unique customer identifier |
| Country | Customer's country |
| Total Invoice Amount | Engineered field (Quantity × Unit Price) |

### Geographic Coverage

The dataset spans multiple countries, led by:

* United Kingdom
* EIRE
* Netherlands
* Germany
* France
* Other European & international markets

### Product Categories

Products span categories including:

* Kitchen Storage
* Tableware
* Kitchen & Dining
* Bathroom
* Rugs & Carpets
* Wall & Window Décor
* Home Appliances
* Cookware
* Smart Home
* Home Décor
* Festive & Seasonal
* Home Furnishings
* Cleaning & Utility
* Bedding & Mattresses
* Storage & Organization
* Garden & Outdoor

---

# 🔍 Data Quality Assessment

The uploaded dataset was examined for completeness, consistency, and analytical readiness.

### Data Quality Results

| Quality Check | Result |
|---|---:|
| Total Transaction Lines | 541,909 |
| Unique Customers | 8,082 |
| Unique Orders/Invoices | 25,900 |
| Product/SKU Codes | 375 |
| Data Sheets Provided | Raw Data, Cleaned Data |

The **Cleaned Data** sheet includes engineered analytical fields — **Invoice Year, Invoice Month, and Total Invoice Amount** — built specifically to support monthwise and yearwise revenue analysis.

The dataset was therefore suitable for exploratory analysis and dashboard development.

---

# 📈 Key Dataset KPIs

Based directly on the uploaded dataset:

| KPI | Result |
|---|---:|
| Total Customers | 8,082 |
| Total Orders | 25,900 |
| Total Sales | ₹11,585,621.15 (~₹11.59M) |
| Average Order Value | ₹447.32 |
| Average Revenue per Customer | ₹1,433.51 |
| Repeat Customers | 3,059 |
| Repeat Customer Rate | 37.85% |
| Repeat Customer Revenue Share | 78.27% |
| Product/SKU Codes | 375 |

The gap between repeat customer rate (37.85%) and repeat customer revenue share (78.27%) highlights that a relatively small group of loyal customers drives the majority of the business.

---

# 📊 Dashboard Design

The Power BI dashboard contains four pages.

## 1. 🏠 Home Page

![Home Page](images/Dashboard1.png)

The landing page introduces TATA Group / TATA CLiQ Home branding and provides navigation to:

* Executive Sales
* Product Performance
* Repeat Customers

The homepage is designed as an executive entry point to the analytics solution.

---

## 2. 📈 Dashboard 1 — Sales & Geographic Analysis

![Sales & Geographic Analysis](images/Dashboard2.png)

### KPI Cards

* Total Customers
* Total Orders
* Total Sales

### Visualizations

* Monthwise Top Sales (bar chart)
* Monthwise Revenue Trend (waterfall / MoM change)
* Countrywise Revenue Distribution (map)
* Top Revenue Generation Countries (donut chart)

This page gives management a complete overview of sales performance and seasonality.

---

## 3. 🛒 Dashboard 2 — Product Performance

![Product Performance](images/Dashboard3.png)

### KPI Cards

* Total Units Sold
* Average Revenue per Customer
* Average Order Value

### Visualizations

* Top Selling Products by Revenue (with SKU-level detail table)
* Top Selling Products by Units Sold (with SKU-level detail table)

This page is particularly useful for assortment planning and inventory decisions.

---

## 4. 👥 Dashboard 3 — Customer & Retention Analysis

![Customer & Retention Analysis](images/Dashboard4.png)

### KPI Cards

* Total Customers
* Repeat Customers
* Repeat Customer Rate

### Visualizations

* Monthwise Repeat Customers Count
* Top Repeating Product Categories (donut chart)
* Top Repeating Products (SKU-level detail table)

This page effectively communicates customer loyalty and retention behavior.

---

# 🎛️ Dashboard Interactivity

The dashboard incorporates interactive slicers for:

### Year

Allows comparison across:

* 2010
* 2011

### Country

Allows the dashboard to be filtered to a specific country or viewed for **All** countries combined.

### Month

Allows users to analyze sales and repeat-customer patterns across all twelve months, from January through December.

The slicers dynamically update the dashboard KPIs and visualizations, enabling users to move from an overall business view to a specific period or market.

---

# 📅 Monthly Sales & Revenue Analysis

| Period | Revenue |
|---|---:|
| H1 (Jan–Jun) | ₹4.36M |
| H2 (Jul–Dec) | ₹7.23M |
| H2 Growth vs H1 | 65.94% |

* **December** is the highest-revenue month at approximately **₹1.74M**.
* **November** follows closely at approximately **₹1.56M**.
* The business shows a sustained revenue acceleration beginning in **September**, driven by festive shopping, promotions, and year-end demand.
* Approximately **62.4% of annual revenue** is generated during the second half of the year.

### Business Insight

Inventory, marketing, staffing, logistics, and promotional budgets should not be distributed evenly across the year. The business should prepare aggressively **before September** to capture the September–December peak.

---

# 🌍 Geographic Revenue Analysis

| Market | Approx. Revenue Share |
|---|---:|
| United Kingdom | 85.13% |
| EIRE | 2.78% |
| Netherlands | 2.62% |
| France | 2.03% |
| Other markets | Remainder |

### Business Insight

The **United Kingdom** is the core market, providing a highly established revenue base — but this also creates **geographic concentration risk**. A downturn in UK demand could materially affect overall revenue.

After the UK, the most promising visible markets for expansion are **EIRE, Netherlands, Germany, France, and Australia**. Rather than aggressively expanding everywhere, the business should identify markets with high repeat-purchase potential, strong average order value, favorable logistics economics, and lower customer acquisition cost — pursued through a **pilot-based expansion strategy**.

---

# 🛒 Product Performance Analysis

### Top Products by Revenue

| StockCode | Product | Category | Revenue |
|---|---|---|---:|
| TCH-KST-1265-0 | Kitchen Drawer Organizer | Kitchen Storage | $342,529 |
| TCH-TBL-1291-2 | Cutlery Set | Tableware | $273,363 |
| TCH-KIT-1028-1 | Stainless Steel Lunch Box | Kitchen & Dining | $236,006 |
| TCH-TBL-1296-7 | Water Glass Set | Tableware | $222,247 |
| TCH-RUG-1246-2 | Round Area Rug | Rugs & Carpets | $216,621 |

### Top Products by Units Sold

| StockCode | Product | Category | Units Sold |
|---|---|---|---:|
| TCH-BTH-1153-1 | Soap Dispenser Set | Bathroom | 176,629 |
| TCH-KST-1265-0 | Kitchen Drawer Organizer | Kitchen Storage | 164,689 |
| TCH-WND-1322-9 | Macrame Wall Hanging | Wall & Window Décor | 64,264 |
| TCH-WND-1328-1 | Blinds | Wall & Window Décor | 55,753 |
| TCH-APP-1103-1 | Tower Fan | Home Appliances | 55,327 |

### Business Insight

Revenue leadership and unit-volume leadership are **not identical** — the Kitchen Drawer Organizer leads in revenue while the Soap Dispenser Set leads in volume. The top five products contribute approximately **17.18% of total revenue**, indicating a reasonably diversified product portfolio. Management should evaluate products using **Revenue + Units + Repeat Purchase Rate** together rather than relying on a single metric.

---

# 👥 Customer Retention Analysis

A repeat customer is defined as a customer who has placed more than one distinct order/invoice.

| Metric | Value |
|---|---:|
| Total Customers | 8,082 |
| Repeat Customers | 3,059 |
| One-Time Customers | 5,023 |
| Repeat Customer Rate | 37.85% |
| Repeat Customer Revenue | ~₹9.07M (78.27% of total) |
| Repeat Customer Avg. Revenue | ~₹2,964 per customer |
| One-Time Customer Avg. Revenue | ~₹501 per customer |

A repeat customer generates approximately **5.9× the revenue** of a one-time customer on average — one of the most important findings in this analysis.

### Monthwise Repeat Customers

| Month | Repeat Customers |
|---|---:|
| November | 673 |
| December | 539 |
| October | 445 |
| September | 400 |
| February | 243 (weakest month) |

### Business Insight

62.15% of customers are currently one-time buyers, representing the **largest untapped opportunity** in the dataset. January and February — the weakest months for repeat purchasing — should be treated as strategic retention months through second-purchase discounts, loyalty points, and personalized re-engagement campaigns.

---

# 🔁 Repeat Purchasing by Category

| Category | Repeat Customers | Share |
|---|---:|---:|
| Cookware | 1,865 | 20.63% |
| Smart Home | 1,844 | 20.4% |
| Home Décor | 1,834 | 20.29% |
| Festive & Seasonal | 1,750 | 19.36% |
| Home Furnishings | 1,748 | 19.33% |

### Business Insight

The relatively balanced distribution indicates that repeat purchasing is **not dependent on a single category**, providing an opportunity to build category-specific loyalty journeys across the portfolio. The top repeating product overall is the **Gift Storage Box**, spanning seasonal, kitchen, décor, bathroom, appliance, cleaning, and bedding products — showing that repeat behavior exists across both replenishment-driven and discretionary purchases.

---

# 💡 Key Business Insights

## 1. Retention Is the Biggest Growth Opportunity

Only **37.85%** of customers are repeat customers, yet they generate **78.27% of revenue**. Customer retention is considerably more valuable than the raw customer count suggests.

---

## 2. The Business Is Highly Seasonal

September through December represents the strongest revenue period, with December alone producing approximately **₹1.74M**. The business should prepare inventory and campaigns well before the peak season.

---

## 3. The UK Is the Core Market

Approximately **85.13% of revenue** comes from the United Kingdom. This provides a strong base but also creates geographic concentration risk that should be addressed through gradual international diversification.

---

## 4. Functional Home Products Perform Strongly

Kitchen, bathroom, tableware, storage, and décor products appear repeatedly among the leading revenue, unit, and repeat-purchase products — suggesting strong, consistent demand for practical, functional home products.

---

# 🚀 Business Recommendations

## 1. Build a Customer Retention & Loyalty Program

Given that repeat customers generate approximately 78.27% of revenue, even a modest increase in repeat-customer conversion could create meaningful incremental revenue.

Recommended actions:

* Second-order discounts
* Loyalty points
* Personalized product recommendations
* Post-purchase email campaigns
* Replenishment reminders
* Category-based promotions
* Personalized offers for inactive customers

---

## 2. Prepare Aggressively for the September–December Peak

H2 revenue is approximately 65.94% higher than H1. Inventory and marketing should be planned around the seasonal demand curve.

Priority categories:

* Tableware
* Kitchen Storage
* Bathroom
* Home Décor
* Smart Home
* Festive & Seasonal products

Inventory should be secured before September, while marketing campaigns should begin ahead of the demand spike.

---

## 3. Increase Basket Size Through Cross-Selling & Selective Expansion

Create product bundles around high-performing categories, e.g.:

* Kitchen Storage + Tableware
* Bathroom + Cleaning & Utility
* Home Décor + Wall & Window Décor
* Cookware + Kitchen & Dining
* Home Furnishings + Bedding

At the same time, pursue **gradual, pilot-based international expansion** into EIRE, Netherlands, Germany, and France — rather than broad simultaneous expansion — while keeping the UK as the core market.

---

# 🛠️ Tools & Technologies

### Power BI

Used for:

* Dashboard development
* KPI cards
* Interactive slicers
* Map & geographic visualization
* Waterfall / trend visualization
* Product and customer segmentation
* Business intelligence reporting

### Microsoft Excel

Used for:

* Source data storage (Raw Data / Cleaned Data)
* Data cleaning and transformation
* Engineered field creation (Invoice Year, Invoice Month, Total Invoice Amount)

### Data Analysis Concepts

The project demonstrates:

* Exploratory Data Analysis
* Data Cleaning & Transformation
* KPI Development
* Customer Retention Analysis
* Seasonal Trend Analysis
* Geographic Revenue Analysis
* Product Performance Analysis
* Business Intelligence
* Data Visualization
* Business Storytelling

---

# 🔄 Project Workflow

```text
Raw E-Commerce Transaction Dataset
        ↓
Data Cleaning & Profiling
        ↓
Data Quality Validation
        ↓
Feature Engineering (Invoice Year, Month, Total Invoice Amount)
        ↓
Customer & Product Segmentation
        ↓
KPI Development
        ↓
Power BI Dashboard (4 Pages)
        ↓
Interactive Drill-Down
        ↓
Business Insights
        ↓
Strategic Recommendations
```

---

# 📂 Repository Structure

```text
Project12-TATA-CLIQ-Ecommerce-Analysis/
│
├── dataset/
│   └── Online_Retail.xlsx
│
├── TATA Sales Dashboard.pbix
│
├── images/
│   ├── Dashboard1.png
│   ├── Dashboard2.png
│   ├── Dashboard3.png
│   └── Dashboard4.png
│
├── Report/
│   ├── TATA CLiQ Analysis Report.pdf
│   └── TATA CLiQ Analysis Report.docx
│
└── README.md
```

---

# 📄 Project Report

A detailed business analysis report is included in the `Report` folder.

The report covers:

* Executive Summary
* Dataset Statistics & Overview
* Overall KPI Performance
* Customer Retention Analysis
* Monthly Revenue Performance
* Geographic Revenue Analysis
* Product Performance Analysis
* Dashboard Assessment
* Business Recommendations

---

# 📌 Key Takeaways

| Area | Finding |
|---|---|
| Customer Base | 8,082 customers |
| Total Sales | ~₹11.59M |
| Total Orders | 25,900 |
| Average Order Value | ₹447.32 |
| Repeat Customer Rate | 37.85% |
| Repeat Customer Revenue Share | 78.27% |
| Peak Revenue Period | September–December |
| Strongest Month | December (~₹1.74M) |
| Dominant Market | United Kingdom (85.13%) |
| Top Revenue Product | Kitchen Drawer Organizer |
| Top Volume Product | Soap Dispenser Set |
| Strategic Opportunity | Retention & seasonal planning |

---

# 🎓 Portfolio Value

This project demonstrates my ability to take a raw e-commerce transaction dataset and transform it into a complete analytical solution.

The project showcases skills in:

**Data Cleaning → Feature Engineering → KPI Development → Dashboard Design → Segmentation → Business Insights → Recommendations**

It demonstrates how data analytics can support e-commerce management in understanding sales performance, customer loyalty, seasonal demand, and product strategy to drive data-driven business growth.

---

# 👨‍💻 Author

**Rishav Kumar Mishra**

Aspiring Data Analyst

📧 Email: iamkmr1999@gmail.com

🔗 GitHub: https://github.com/iamkmr19

💼 LinkedIn: https://www.linkedin.com/in/kmrishav19/

---

⭐ If you found this project useful, consider giving this repository a Star!
