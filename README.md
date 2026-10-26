# Wildberries Seller Financial Dashboard (Power BI)

A Power BI dashboard for a Wildberries seller that shows **real profit per product**, not just revenue.

![Dashboard](Снимок%20экрана%202026-06-21%20101612.png)

## Business question
Sales were growing, but the seller did not see more money. Where does the revenue go?

## What the dashboard shows
- Revenue, cost of goods, marketplace commission, logistics and returns — per product and in total
- Real profit = revenue − cost − commission − logistics − returns − advertising
- Products with the highest share of returns
- Regions where orders bring revenue but not profit

## Key finding
Revenue was **55.7M**, but logistics took **13.6M** (about a quarter of revenue) and commission another **5.5M**. This was not visible in the regular sales table.

## Data & stack
- **Data:** orders and sales from PostgreSQL (WB API export), cost price and tariffs from Google Sheets
- **Power BI:** data model with relationships, DAX measures, Power Query transformations

## Author
Yernur Yessenkeldi — [LinkedIn](https://www.linkedin.com/in/yernur-yessenkeldi-737437387/)
