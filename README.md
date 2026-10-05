# Supply Chain Analytics Dashboard

![Dashboard](dashboard.png)

## Business problem
Is the supply chain healthy? Are orders delivered on time and in full, what is causing delays, where is stock too high or running out, and where does revenue come from?

## Key findings
- Only 66% of orders arrive on time (target 90%). Same-day orders are worst at 12.5%.
- Root cause: orders take about 5 days to leave the warehouse, but Same-day is promised in 2 days.
- About 162 days of stock held (healthy is 30 to 60), with no stockouts.
- Wholesale brings in 69% of revenue. Asia is the top region at 39%.

## Recommendations
1. Cut warehouse processing time from about 5 days to 3 or less.
2. Stop promising 2-day delivery on Same-day until processing is faster.
3. Add buffer to promised dates for Air and Rail.
4. Reduce stock levels, since there are no stockouts.

## Tools
Power BI, DAX. Dataset: 12,000 orders, 6 tables, star schema.
