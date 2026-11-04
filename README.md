# Retail Sales Analysis | Excel & Power BI

A retail sales analysis project completed as part of the **Conorise Infotech Data Analytics Internship**. The project uses Microsoft Excel for the source data and summary analysis, and Power BI to present sales performance through an interactive dashboard and a separate business-insights page.

> **Project focus:** understand sales performance, compare product categories, examine monthly trends and customer demographics, and turn the findings into practical business recommendations.

## Project files

| File | Description |
|---|---|
| `retail_sales_dataset.xlsx` | Excel workbook containing the transaction-level dataset and an `Analysing Summary` worksheet. |
| `Retail Sales Dashboard.pbix` | Power BI report containing the interactive `Dashboard` page and the `Business Insights` page. |

## Tools used

- **Microsoft Excel** – inspect and validate the transaction data, review summary calculations, and prepare the source workbook.
- **Microsoft Power BI Desktop** – create KPI cards, charts, slicers, and the business-insights page.

## Dataset overview

The workbook contains **1,000 transaction records** and the following nine fields:

| Column | Description |
|---|---|
| `Transaction ID` | Unique transaction identifier. |
| `Date` | Transaction date. |
| `Customer ID` | Customer identifier. |
| `Gender` | Customer gender recorded in the dataset. |
| `Age` | Customer age. |
| `Product Category` | Product category purchased. |
| `Quantity` | Number of units purchased in the transaction. |
| `Price per Unit` | Price recorded for one unit. |
| `Total Amount` | Transaction amount. |

**Date coverage:** 1 January 2023 to 1 January 2024. The dashboard heading is labelled `2023`; the source workbook includes a record dated 1 January 2024 as well. Consider updating the report heading or date filter so that it accurately describes the selected reporting period.

## Data validation

The supplied workbook was checked for basic data-quality issues:

- 1,000 transaction rows were present.
- No blank values were found in the nine dataset columns.
- No duplicate `Transaction ID` values were found.
- `Total Amount` matched `Quantity × Price per Unit` for all inspected rows.

These checks describe the supplied workbook. They do not establish that the source data is complete or accurate beyond the fields and consistency checks available in the file.

## Dashboard contents

### Page 1 — Dashboard

The main dashboard includes six KPI cards:

- Total Revenue
- Total Units Sold
- Total Orders
- Average Order Value
- Total Customers
- Total Categories

It also includes these visual analyses:

- Monthly sales trend
- Total sales by age group
- Total sales by product category
- Total sales by gender
- Total quantity by product category

Interactive slicers are provided for **Year, Month, Gender, Age Group, and Category**.

### Page 2 — Business Insights

The second report page summarises five business recommendations based on the available analysis:

1. Review weaker sales months and test seasonal promotions.
2. Monitor category revenue and unit volume when planning category promotions and inventory.
3. Study age-group preferences and test suitable offers for lower-revenue groups.
4. Compare customer sales patterns and test marketing messages with measurable results.
5. Capture additional product, region, cost, discount, and inventory fields to support deeper analysis.

Recommendations are proposals to test, not proof that a specific action will increase sales. Their impact should be measured after implementation.

## Key results

The following values are calculated from the supplied workbook and reflected in the project analysis:

| Metric | Result |
|---|---:|
| Total revenue / transaction amount | 456,000 |
| Total units sold | 2,514 |
| Total transactions | 1,000 |
| Average order value | 456 |
| Distinct customers | 1,000 |
| Product categories | 3 |

### Sales by category

| Product category | Revenue | Units sold |
|---|---:|---:|
| Electronics | 156,905 | 849 |
| Clothing | 155,580 | 894 |
| Beauty | 143,515 | 771 |

### Monthly sales highlights

- **Highest month:** May — 53,150.
- **Lowest month:** September — 23,620.

### Customer highlights

- Female customers account for 232,840 in revenue (51.06%).
- Male customers account for 223,160 in revenue (48.94%).
- The 45–54 age group has the highest revenue among the age groups shown: 97,235.

> **Currency note:** The dataset does not contain a currency-code field. The Power BI report may display a currency symbol as a formatting choice; confirm the intended currency before interpreting or publishing the amounts as a specific currency.

## Business recommendations

Based on the patterns in the dataset, the project proposes the following actions:

| Finding | Suggested action | How to measure it |
|---|---|---|
| September has the lowest monthly sales. | Test targeted offers or seasonal campaigns during weaker sales periods. | Monthly revenue, transaction count, and units sold. |
| Electronics has the highest category revenue, while Clothing has the highest unit volume. | Review category-level demand and stock availability; test promotions without neglecting high-volume categories. | Category revenue, units sold, and stock availability. |
| The 45–54 age group has the highest revenue; the 18–24 group has the lowest. | Study category preferences and test relevant offers for younger customers. | Revenue and average order value by age group. |
| Female and male revenue contributions are relatively close. | Maintain broad customer coverage and test campaign messages against measurable outcomes. | Revenue by gender; campaign conversion metrics require campaign data. |
| Product, region, cost, discount, and inventory details are not available. | Expand data collection to support product-level, regional, and profitability analysis. | Product revenue, profit margin, regional sales, and inventory metrics once those fields are collected. |

## How to open the project

1. Download or clone this repository.
2. Open `retail_sales_dataset.xlsx` in Microsoft Excel to review the source data and summary worksheet.
3. Install or open **Power BI Desktop**.
4. Open `Retail Sales Dashboard.pbix` in Power BI Desktop.
5. Use the slicers on the `Dashboard` page to explore the report. Open `Business Insights` to review the recommendations.

If you replace or update the Excel source data, refresh the data in Power BI and recheck the KPI totals, chart values, and date range before publishing the updated report.

## Limitations and opportunities for improvement

The dataset supports transaction, category, monthly, and customer-demographic analysis. It does **not** include:

- Individual product names or product IDs
- Store, city, state, or regional information
- Cost of goods sold or other expense fields
- Profit or profit margin
- Discounts or promotional campaign details
- Inventory or stock-on-hand information

As a result, this version cannot reliably calculate profit, compare regional performance, identify individual best-selling products, or measure marketing campaign effectiveness. These analyses would require additional source fields.

## Project objective

Demonstrate an end-to-end, business-focused retail sales analysis using Excel and Power BI: validate the available data, calculate meaningful KPIs, identify sales and customer patterns, communicate insights visually, and recommend measurable next steps.

---

**Project:** Retail Sales Analysis  
**Program:** Conorise Infotech — Data Analytics Internship  
**Tools:** Microsoft Excel | Microsoft Power BI
