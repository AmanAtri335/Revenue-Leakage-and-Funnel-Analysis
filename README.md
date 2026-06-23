# 📊 Revenue Leakage & Funnel Analysis using SQL + Power BI

![Dashboard Overview](Assets/Dashboard_Overview.png)

## 📌 Project Overview

Revenue growth alone does not always reflect business health.

This project analyzes the **Olist Brazilian E-Commerce Dataset** to identify hidden revenue leakage and operational inefficiencies across the order lifecycle.

By combining **SQL** for data extraction and transformation with **Power BI** for visualization, the project uncovers how funnel drop-offs and delivery issues impact realized revenue.

The analysis helps answer a critical business question:

> **"Where is revenue being lost, and what operational factors are causing it?"**

---

## 🎯 Business Problem

E-commerce companies often focus on increasing sales while overlooking operational inefficiencies that silently reduce revenue realization.

This project addresses the following questions:

* Where are customers dropping off in the order funnel?
* Why are some orders not converting into successful deliveries?
* How do delivery delays affect business performance?
* What operational issues contribute to revenue leakage?
* How can businesses improve funnel efficiency and revenue realization?

---

## 🛠 Solution Approach

### 1. Data Extraction & Transformation

Using SQL:

* Extracted data from multiple relational tables.
* Cleaned inconsistent and missing records.
* Performed joins across:

  * Orders
  * Customers
  * Payments
  * Sellers
  * Reviews
  * Products

### 2. Data Modeling

Created a relational model to connect customer transactions across the entire order lifecycle.

### 3. KPI Development

Designed business metrics to track:

#### Revenue Metrics

* Total Revenue
* Realized Revenue
* Revenue Leakage

#### Funnel Metrics

* Order Approval Rate
* Order Placement Rate
* Delivery Success Rate
* Funnel Conversion %

#### Operational Metrics

* On-Time Delivery %
* Late Delivery %
* State-wise Delivery Delays

### 4. Dashboard Development

Built interactive Power BI dashboards for:

* Revenue Leakage Analysis
* Funnel Conversion Monitoring
* Delivery Performance Tracking
* Regional Performance Analysis

---

# 📸 Dashboard Preview

## 1️⃣ Executive Dashboard

![Dashboard Overview](Assets/Dashboard_Overview.png)

The executive dashboard provides a high-level overview of:

* Revenue Performance
* Funnel Conversion
* Delivery Metrics
* Revenue Leakage Indicators

---

## 2️⃣ Funnel Analysis Dashboard

![Funnel Analysis](Assets/Funnel_Analysis.png)

### Key Findings

* Orders drop across multiple stages:

  * Approved Orders
  * Shipped Orders
  * Delivered Orders

* Overall conversion rate remains close to **97%**.

* Small inefficiencies create significant revenue loss when scaled across thousands of transactions.

### Business Insight

Even a 1–3% drop in funnel conversion can translate into substantial revenue leakage.

---

## 3️⃣ Delivery Performance Dashboard

![Delivery Performance](Assets/Delivery_Performance.png)

### Key Findings

* Approximately **8% of orders are delivered late**.
* Certain states experience significantly higher delivery delays.
* Delayed deliveries contribute to:

  * Customer dissatisfaction
  * Order cancellations
  * Revenue loss

### Business Insight

Operational inefficiencies directly impact revenue realization and customer experience.

---

## 4️⃣ State-Wise Delivery Delay Analysis

![State Analysis](Assets/State_Delay_Analysis.png)

### Insights

* Delivery performance varies across regions.
* Some states consistently experience higher delay rates.
* Geographic analysis helps identify operational bottlenecks.

### Business Value

Supports targeted logistics optimization and regional performance improvement.

---

## 📊 Key Insights

### Revenue Leakage Is Systematic

Revenue loss occurs repeatedly at specific stages of the order lifecycle rather than randomly.

### Funnel Efficiency Matters

Strong sales performance alone is insufficient if orders fail to progress through the funnel.

### Delivery Delays Impact Revenue

Late deliveries contribute significantly to funnel drop-offs and failed order completion.

### Operational Performance Drives Business Outcomes

Improving fulfillment efficiency can increase realized revenue without increasing sales volume.

---

## 📈 Results

### Funnel Performance

* Identified conversion losses between order stages.
* Quantified revenue leakage across the order lifecycle.

### Delivery Analysis

* Revealed operational bottlenecks causing delayed deliveries.
* Highlighted states with higher logistics inefficiencies.

### Business Impact

* Improved visibility into revenue realization.
* Enabled data-driven operational decision-making.

---

## 🧰 Tools & Technologies

| Tool        | Purpose                                    |
| ----------- | ------------------------------------------ |
| SQL         | Data Extraction, Cleaning & Transformation |
| Power BI    | Dashboard Development & Visualization      |
| DAX         | KPI & Measure Calculations                 |
| Power Query | Data Preparation                           |
| Excel / CSV | Dataset Storage                            |

---

## 📂 Project Structure

```text id="98plja"
Revenue-Leakage-Analysis/
│
├── Assets/
│   ├── Dashboard_Overview.png
│   ├── Funnel_Analysis.png
│   ├── Delivery_Performance.png
│   └── State_Delay_Analysis.png
│
├── Power BI File/
│   └── Revenue_Leakage_Analysis.pbix
│
├── SQL Scripts/
│   └── Data_Processing.sql
│
├── DataSource.md
├── Insights.md
│
└── README.md
```

---

## 📚 Dataset Information

This project uses the **Olist Brazilian E-Commerce Dataset**, a real-world dataset representing a multi-vendor online marketplace operating in Brazil.

The dataset captures the complete order lifecycle:

* Customer Purchase
* Payment Processing
* Seller Fulfillment
* Delivery Tracking
* Customer Reviews

The relational structure closely resembles real-world production databases, making it ideal for business intelligence and analytics projects.

---

## 🚀 How to Use

### Step 1

Clone or download the repository.

### Step 2

Open the Power BI file:

```bash
Power BI File/Revenue_Leakage_Analysis.pbix
```

### Step 3

Explore:

* Revenue KPIs
* Funnel Conversion Metrics
* Delivery Performance Trends
* Regional Analysis

---

## 💡 Key Learnings

* Revenue growth alone does not indicate business health.
* Funnel conversion is a critical business metric.
* Delivery performance directly impacts revenue realization.
* Small operational inefficiencies compound into significant losses.
* Data-driven insights can uncover hidden business problems.

---

## 🚀 Future Improvements

### Predictive Analytics

* Late Delivery Prediction
* Revenue Leakage Forecasting

### Customer Analytics

* Customer Segmentation
* Customer Lifetime Value (CLV)

### Automation

* Automated ETL Pipelines using Python
* Scheduled Dashboard Refreshes

### Advanced Analytics

* Seller Performance Scoring
* Product Category Analysis
* Churn Risk Assessment

---

## 💼 Business Value

This project demonstrates how analytics can uncover hidden operational inefficiencies that directly affect profitability.

Rather than focusing solely on revenue growth, the analysis emphasizes:

* Revenue Realization
* Funnel Optimization
* Operational Excellence
* Customer Experience

The insights generated can help organizations improve profitability without increasing customer acquisition costs.

---

## 👨‍💻 Author

**Aman Atri**

Aspiring Data Analyst | SQL | Power BI | Business Intelligence | Data Analytics

⭐ If you found this project useful, consider starring the repository.



