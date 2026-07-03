# Supply Chain Management

Analytics project looking at sales, inventory, and supplier performance across regions. Built the data model in Excel, wrote SQL queries to explore it, and made dashboards in Power BI and Tableau.

## What's in here

- `supply_chain_project_2.xlsx` - the main data model with fact and dimension tables, a data dictionary, and KPI/summary sheets
- `supply_chain_sql.sql` - SQL queries used to explore customer, store, inventory, and sales data
- `supply_chain_powerbi.pbix` - Power BI dashboard
- `supply_chain_tableau.twbx` - Tableau dashboard

## Data model

Star schema with one main fact table (Fact_Orders) and a few dimension tables:

- Dim_Product - product catalog, cost, price, category
- Dim_Supplier - supplier info, tier, reliability score
- Dim_Warehouse - location and capacity
- Dim_Customer - region, segment
- Fact_Inventory - inventory levels and value

Column-level details are in the Data_Dictionary sheet inside the Excel file.

## What it covers

- Revenue by region
- On-time vs delayed order delivery
- Gross margin by product category
- Supplier reliability
- Inventory value by product family

## Tools

SQL, Excel, Power BI, Tableau
