# Sales Performance Dashboard (Power BI)

An interactive Power BI dashboard analyzing 2023 sales data by region, product category, customer type, and payment method.

![Dashboard Preview](images/dashboard.png)

## Business Questions
- How much revenue and volume did we generate overall?
- Which regions and product categories sell the most?
- How do new and returning customers contribute to each category?
- Which payment methods do customers use most?
- How do sales change over time?

## Dataset
`sales-data_01.csv` has ~1,000 sales records with these fields: Product ID, Sale Date, Sales Rep, Region, Sales Amount, Quantity Sold, Product Category, Unit Cost, Unit Price, Customer Type, Discount, Payment Method, and Sales Channel.

## Data Cleaning (Power Query)
- Removed blank and duplicate rows
- Dropped the unused `Customer_na` column
- Fixed data types (dates, numbers)
- Standardized the Region and Sales Rep fields

## Key Insights
- Total revenue was **$5.02M** from **25K units** sold.
- **Clothing** was the top category (~$1.31M) and **North** was the top region (~$1.37M); **South** was the lowest (~$1.15M).
- Credit card (35%) and bank transfer (34%) were the most used payment methods, with cash at 31%.
- New and returning customers contributed about equally overall, but Furniture relied more on returning customers.

## Tools
Power BI Desktop · Power Query · DAX

## Files
| File | Description |
|---|---|
| `project_01.pbix` | Power BI dashboard file |
| `sales-data_01.csv` | Raw dataset |
| `images/` | Dashboard screenshots |

## How to Open
Download `project_01.pbix` and open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).

## Author
**Moe Khant Zaw** 
