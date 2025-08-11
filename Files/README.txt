Dataset
Source: liquor.csv (Cleaned dataset)
Fields used include:
bottle_qty, btl_price, category_name, county, date, liter_size, state_btl_cost, store_location, total, vendor, description

Dashboard Theme & Title
Theme: Light Violet
Title: "Liquor Sales Performance"

Page Structure
This is a one-page major KPI and insights dashboard.
-KPI Cards (Top Row)
-Total Sales → SUM(total)
-Total Bottles Sold → SUM(bottle_qty)
-Average Bottle Price → AVERAGE(btl_price)
-Total Vendors → DISTINCTCOUNT(vendor)
-Total Stores → DISTINCTCOUNT(store)

Store Performance (Column Chart)
-X-Axis: store_location
-Y-Axis: SUM(total)
-Sorted descending by total sales
-Highlight top-performing store

Top 5 Vendors by Revenue (Bar Chart)
-X-Axis: SUM(total)
-Y-Axis: vendor
-Filter: Top N = 5 by total sales


Category with Most Bottles Sold (Column Chart)
-X-Axis: category_name
-Y-Axis: SUM(bottle_qty)
-Sorted descending

Sales Trend Over Time (Line Chart)
-X-Axis: date (Month-Year)
-Y-Axis: SUM(total)
-Sorted chronologically

Sales by County (Map)
-Location: county
-Values: SUM(total)

Highest Revenue Product (Table)
-Columns: description, SUM(total)
-Sorted descending
-Filter: Top 1