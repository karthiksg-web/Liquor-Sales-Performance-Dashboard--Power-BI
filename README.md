
# Liquor Sales Performance Dashboard-Power BI

## Project Overview
This project involves creating an interactive and visually appealing Power BI dashboard to analyze liquor sales data.
The goal is to provide key insights for stakeholders, including sales performance, vendor contributions, category analysis,
pricing trends, and geographical distribution.

---

## Acknowledgements
-Thanks to all contributors and dataset providers who made this analysis possible.
-Special thanks to the team that cleaned and structured the liquor sales data.

## API Reference
-No API integrations were used in this project — all data comes from a local CSV dataset (liquor.csv).

## Appendix
  - Dataset: liquor.csv (cleaned)
  - Tool: Microsoft Power BI
  - Theme: Light Violet
  - Title: "Liquor Sales Performance"

---


## Key Insights Delivered
- Identification of top-performing stores and vendors.
- Categories generating the highest sales volume.
- Seasonal and monthly sales patterns.
- Regional sales distribution across counties.
- Pricing analysis for better margin tracking.

---

## Tools Used
- **Microsoft Power BI Desktop**
- **DAX** for calculated measures:
  - Total Sales = SUM(liquor[total])
  - Total Bottles Sold = SUM(liquor[bottle_qty])
  - Average Bottle Price = AVERAGE(liquor[btl_price]) 
  - Total Vendors = DISTINCTCOUNT(liquor[vendor])
  - Total Stores = DISTINCTCOUNT(liquor[store])
  - Profit Margin = SUM(liquor[btl_price]) - SUM(liquor[state_btl_cost])


---

## Usage
  1. Open the `.pbix` file in Power BI Desktop.
  2. Load the provided liquor sales dataset.
  3. Interact with the dashboard by applying filters and slicers.
  4. Review KPIs, trends, and maps for decision-making.

---

## Author
This dashboard was prepared to provide a one-page overview of liquor sales performance for management decision-making.

Karthik S G — Power BI Dashboard Developer.
