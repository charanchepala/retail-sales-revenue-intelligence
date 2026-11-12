# Retail Sales Analytics & Revenue Intelligence

An end-to-end Excel portfolio project analyzing 700 synthetic retail orders across products, customers, regions, and sales channels.

## Business problem
This portfolio project uses a realistic, **synthetic dataset** to demonstrate practical spreadsheet analytics. It is not company or customer data.

## Files
- `Retail_Sales_Revenue_Intelligence.xlsx` — Main workbook with raw data, VLOOKUP enrichment, CONCAT key, calculations, KPI dashboard and charts.
- `README.md` — Project overview, usage, findings and interview talking points.

## Tools and skills demonstrated
- Excel formulas: VLOOKUP, IFERROR, SUMIF, SUM, COUNTA, TEXT, CONCAT.
- Data enrichment using product and customer lookup tables.
- Data preparation and delimiter splitting workflow (Text to Columns).
- KPI analysis: revenue, gross sales, profit, average order value and profit margin.
- Dashboard charts for monthly trend, category and regional performance.

## How to use
1. Open the `.xlsx` workbook in Microsoft Excel (Excel 365 or Excel 2021 recommended).
2. Start with `Dashboard`, then inspect the `Analysis` sheet for the supporting calculations.
3. Review the raw and cleaned data sheets. Formula cells are intentionally visible so the work can be audited.
4. Change or append records in the source data tables and recalculate in Excel. Some summary formulas use modern Excel functions where noted.

## Key findings in this sample
- The workbook contains 700 generated orders for the 2025 calendar year.
- Revenue and profit are summarized by month, product category, region and sales channel.
- The sample includes 10 products, 80 customers and three sales channels.

## Interview talking points
- Why did you separate raw data and lookup tables? To keep source transactions unchanged and maintain reusable master data.
- How does VLOOKUP work here? It matches Product_ID or Customer_ID in the first column of a lookup range and returns a selected field using exact match FALSE.
- Why use IFERROR? To prevent lookup errors from breaking the analysis and to show a controlled fallback.
- What does the customer key demonstrate? CONCAT joins customer and product identifiers with a hyphen delimiter; Text to Columns can split it back into fields.

## Data integrity note
All names, transactions, salaries, attendance records, and business values are generated for demonstration. Findings describe this sample only and should not be represented as real-world company results.

## Suggested resume wording
After opening the workbook, checking the formulas, and being able to explain the analysis, you can list this under **Projects**. Do not list it as employment or claim business impact outside this synthetic dataset.
