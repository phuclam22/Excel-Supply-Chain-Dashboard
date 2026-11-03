# Supply Chain & Inventory Management Dashboard

A comprehensive, data-driven Excel dashboard designed to optimize procurement operations, monitor vendor performance, and prevent capital stagnation in retail inventory.

![Dashboard Overview](https://i.postimg.cc/2YKx4W4L/Screenshot-2026-11-03-112656.png)

## Project Objective
In the fast-paced Retail and FMCG sectors, balancing stock availability with capital liquidity is a critical challenge. This project aims to build an end-to-end automated reporting system entirely within **Microsoft Excel**, bypassing the need for expensive BI tools. 

The dashboard provides actionable insights into:
* **Procurement Efficiency:** Tracking purchase order (PO) statuses and pending delivery rates.
* **Vendor Management:** Identifying top-performing suppliers based on transaction volume and value to support contract negotiations.
* **Inventory Health:** Monitoring physical stock-out and balance rates to prevent dead stock and optimize reorder points.

## Tech Stack & Methodology
* **Data Source:** Raw transactional data consisting of Purchase Orders, Product Items, Pricing, and Delivery Statuses.
* **Data Modeling:** Utilized **Power Pivot (Data Model)** to handle multi-dimensional data without bogging down the workbook, bypassing traditional flat-table VLOOKUPs.
* **Calculations:** Formulated dynamic KPIs (e.g., Pending PO %, Distinct Vendor Count) using **Data Analysis Expressions (DAX)** directly within Excel.
* **Data Visualization:** Built an interactive, dark-themed UI featuring interconnected PivotCharts (Donuts, Columns, Bars) and synchronized Slicers (Report Connections) for real-time data slicing.

## Key Business Insights
1. **The Inventory Paradox:** **Item-2** drives the highest purchase volume and outbound inventory (69,229 units) but simultaneously accounts for the largest trapped capital with 19,581 units lingering in physical stock balance.
2. **Vendor Consolidation:** **Vendor-7** is the dominant strategic partner, securing the highest order quantity (4,320) and capturing $65.5K in total purchase value, presenting a prime opportunity for volume-discount negotiations.
3. **Operational Bottlenecks:** The overall Pending PO rate stands at an optimal **26%**; however, isolating specific high-value items reveals localized fulfillment delays that require immediate supply chain intervention.

## How to Use This Project
1. Download the `supply-chain_inventory-procurement.xlsx` file from this repository.
2. Open the file in **Microsoft Excel** (Version 2016 or newer recommended for full Power Pivot compatibility).
3. Navigate to the `Dashboard_New` tab.
4. Use the interactive Slicers on the left panel (Year, Month, Product, Vendor) to filter the metrics dynamically.
