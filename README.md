# Interactive Superstore Sales Performance Dashboard (Power BI)

## Project Overview
This repository showcases a 4-page interactive dashboard engineered to clean, structure, and visualize **9,994 transaction records** across **773 unique customers**. The primary objective of this project was to establish an enterprise-grade reporting framework that uncovers operational sales trends, regional performance gaps, and profitability metrics.

---

## Technical Architecture & Modeling
* **Data Transformation (Power Query ETL):** Enforced stringent data-quality rules to sanitize incoming records, eliminate data structural formatting anomalies, and cast appropriate numeric types.
* **Relational Data Modeling:** Architected a robust Star Schema consisting of a centralized **FACT table** mapped directly to logical **LOCATION** and **PRODUCT** dimension tables.
* **Advanced DAX Formulas:** Programmed **11+ complex DAX measures** and calculated columns to evaluate custom sales velocities, tracking targets, and time-intelligence performance profiles.

---

## Canvas Layout Breakdowns (4-Page Report)
1. **Executive Sales Overview:** High-level dynamic KPI cards tracking total gross sales, margins, and volume counts.
2. **Regional Performance Matrix:** Spatial mapping and deep dives into location performance metrics to identify geographical growth sectors.
3. **Product & Category Analysis:** Performance ranking profiles isolating key inventory movers from low-velocity items.
4. **Customer Insights Ledger:** Dedicated tabular and behavioral views tracking transaction densities across the 773-customer cohort.

---

## How to Interact with this Project
1. Download the `.pbix` file from this repository.
2. Open the file natively inside **Power BI Desktop**.
3. Toggle the dynamic slicers, date bounds, and visual drill-downs to explore live cross-filtering patterns.
 
