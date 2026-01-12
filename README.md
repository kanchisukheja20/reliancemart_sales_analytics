# D-Mart Store — Sales Analysis (Power BI)

**Short description:** Interactive Power BI report containing a complete sales analysis for D‑Mart. The report uses cleaned source tables: `Customers_cleaned`, `Inventory_Snapshot_cleaned`, `Products_cleaned`, `Returns_cleaned`, `Sales_Transactions`, and `Warehouses_cleaned`.

---

## Table of Contents
- [Introduction](#introduction)
- [Dataset / Inputs](#dataset--inputs)
- [Tech Stack](#tech-stack)
- [How to Open](#how-to-open)
- [Usage](#usage)
- [Key Analyses & Features](#key-analyses--features)
- [Results & Insights](#results--insights)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Introduction
This repository contains an interactive Power BI report for D‑Mart store sales analysis. The report (file: `dmart_store/d mart test kanchi.pbix`) presents operational KPIs, visual analysis across states, brands and categories, and insights to support business decisions.

- **Purpose:** Provide stakeholders and analysts with an interactive dashboard to explore sales performance, profitability, and product/warehouse-level trends.
- **Audience:** Business analysts, data analysts, product managers, and decision-makers.

---

## Dataset / Inputs
Describe the datasets the report uses (placeholders below — replace with exact info if available):

- **Typical sources:** Sales transactions (orders), product master, warehouse/master data, discounts/returns tables.
- **Format:** CSV / Excel / SQL database (Power Query connects to original sources inside the PBIX file).
- **Notes:** The report file includes queries and transformations performed in Power Query; raw source files are not included in this repository by default. If you redistribute data, ensure no sensitive or PII is shared.

---

## Tech Stack
- Power BI Desktop (.pbix)
- Power Query (data preparation)
- DAX (measures and KPIs)
- Optional: Python / R (if used for preprocessing — replace if not applicable)

---

## How to Open
1. Install Power BI Desktop (free) from Microsoft if you don't already have it.
2. Open `dmart_store/d mart test kanchi.pbix` in Power BI Desktop.
3. To refresh data, configure the data source credentials (if the report uses external databases or files).

---

## Usage
- Navigate through report pages to view KPIs, state and brand-level charts, and category breakdowns.
- Use the top filters and slicers (e.g., `warehouse name`) to focus the report on specific warehouses, regions, time periods or categories.
- To modify or extend the report, edit queries in Power Query and update or add DAX measures as needed.

---

## Key Analyses & Features ✅
The report contains the following common analyses and interactive visuals (as implemented in the PBIX file):

- KPI tiles: customer count, total sales, total quantity sold, total discount, net sales, gross profit, profit margin %
- Sales by state (bar chart) to compare regional performance
- Sales trend by year (area/line chart)
- Gross profit by category (donut / pie)
- Net sales by brand (ranked bar chart)
- Warehouse filter to drill into location-level performance and margins
- Narrative / insight card area (text box) highlighting key business observations

---

## Results & Insights 🔍
Example findings shown in the report (these are presented within the PBIX as of the saved version):

- Example KPIs: Total Sales, Net Sales, Gross Profit, Profit Margin and customer counts are surfaced as top-level indicators.
- Regional highlight: Maharashtra shows highest total sales across states.
- Brand detail: `PurePlus` appears as a top brand followed by `TechNova` in the Net Sales ranking.
- Warehouse insight: Bengaluru Central Warehouse shows strong gross profit for the Personal Care category (example margin shown in the report: ~34.58%).

Replace or expand this section with updated insights once you refresh or update the underlying data.

---

## Project Structure
```
├── dmart_store/
│   └── d mart test kanchi.pbix   # Power BI report (interactive dashboard)
├── data/                         # (Optional) raw/processed data used to build the PBIX
├── docs/                         # (Optional) exported report pages or documentation
├── reports/                       # (Optional) static exports (PDF/PNG) of visualizations
├── README.md
└── LICENSE
```

> Note: The actual raw data files are typically large and are often not tracked in the repository. If you want the exact dataset used to build the PBIX, add a `data/` folder with a short README describing source files and any required transformations.

---

## Contributing
- If you want to improve the report (new measures, visuals, or fixes), please fork the repo and open a PR with a clear description of changes.
- If you don't have Git workflow for `.pbix` files, consider saving the Power Query steps and DAX measures in a companion documentation file or extract them into templates for better version control.
- For major changes, open an issue first to discuss the approach.

---

## License
See the `LICENSE` file for licensing details. Modify as necessary for your project.

---

## Contact
- GitHub: `kanchisukheja20`
- Email: `kanchisukheja20@gmail.com`

If you'd like, I can: add an exported screenshot of the report, a short usage GIF, or a small guide on how to refresh and repoint the data sources — tell me which you'd prefer and I'll add it to the README.