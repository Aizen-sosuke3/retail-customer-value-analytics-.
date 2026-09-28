# 🛒 Retail Customer Value & Profitability Analytics

An end-to-end data analytics project designed to help a regional retail company optimize customer retention, segment high-value buyers, and identify loss-making product categories using **SQL** and **Power BI**.

---

## 📊 Executive Summary
Management lacked visibility into true customer lifetime value and product-level profitability. By executing an advanced **RFM (Recency, Frequency, Monetary)** segmentation model via SQL and visualizing the metrics in an interactive Power BI dashboard, this project highlights actionable strategies to boost retention and cut unprofitable operational overhead.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Database & Querying:** PostgreSQL (CTEs, Window Functions, Joins, Aggregations)
* **Business Intelligence:** Power BI (DAX measures, interactive slicers, KPI visual cards)
* **Data Modeling & Analysis:** RFM Segmentation, Cohort Retention Analysis, Product Margin Matrix

---

## 📂 Repository Structure
```text
├── sql/
│   ├── 01_data_cleaning.sql          # Initial data preprocessing and hygiene checks
│   ├── 02_rfm_segmentation.sql       # Customer value scoring using CTEs and NTILE()
│   └── 03_product_profitability.sql  # Category margin and loss analysis queries
├── dashboards/
│   └── executive_overview.pdf        # Exported high-level executive report
└── README.md
