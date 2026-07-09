# AdventureWorks Sales Analytics Dashboard

A Power BI report built on the AdventureWorks dataset, analyzing sales, customer, and product performance across an interactive multi-page dashboard.

## Overview

This report gives leadership a single view into sales performance, broken down by executive summary, customer behavior, product mix, and regional distribution. It replaces static spreadsheet reporting with a drillable, filterable dashboard.

## Dashboard Pages

| Page | Purpose |
|---|---|
| **Exec Details** | High-level KPIs and trends for leadership — the "first five seconds" view |
| **Customer Detail** | Customer-level breakdown: segments, order history, retention patterns |
| **Product Detail** | Product-level performance: category mix, top/bottom sellers, margins |
| **Map** | Geographic distribution of sales by region/territory |

## Screenshots

> Add exported PNGs of each page here, then reference them below.
> `File > Export > Export to Image` in Power BI Desktop, or a screen capture at 1920x1080.

```
docs/screenshots/exec-details.png
docs/screenshots/customer-detail.png
docs/screenshots/product-detail.png
docs/screenshots/map.png
```

<!--
![Exec Details](docs/screenshots/exec-details.png)
![Customer Detail](docs/screenshots/customer-detail.png)
![Product Detail](docs/screenshots/product-detail.png)
![Map](docs/screenshots/map.png)
-->

## Key Metrics

> Replace with the actual measures once confirmed in Power BI Desktop — the compressed data model can't be read outside the app, so these are placeholders based on the visuals present.

- Total Sales / Revenue
- Total Profit / Margin %
- Order Count
- Sales by Region (map)
- Top N Products / Categories

## Tech Stack

- **Power BI Desktop** — data modeling, DAX measures, report design
- **Power Query (M)** — data transformation and cleaning
- **Custom Visuals**:
  - Race Bar Chart (animated ranking-over-time chart)
  - tCard (KPI card visual)

## Data Source

AdventureWorks sample dataset (Microsoft's standard demo dataset for a fictional bicycle manufacturer), covering sales orders, products, customers, and territories.

## Repository Structure

```
AdventureWorks-Sales-Dashboard/
├── AdventureWorks_Report.pbix     # Main Power BI report file
├── data/                          # Source data files (if not using a live connection)
├── docs/
│   └── screenshots/               # Exported dashboard page images
├── .gitignore
└── README.md
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/AdventureWorks-Sales-Dashboard.git
   ```
2. Open `AdventureWorks_Report.pbix` in **Power BI Desktop**.
3. If prompted, update the data source path/connection to point to your local AdventureWorks data.
4. Explore the four report pages using the tabs at the bottom.

## Author

Pasang (Roshan) Sherpa Tuladhar
Master of Data Analytics, University of Niagara Falls Canada

## License

This project is for portfolio and educational purposes. AdventureWorks is a sample dataset provided by Microsoft.
