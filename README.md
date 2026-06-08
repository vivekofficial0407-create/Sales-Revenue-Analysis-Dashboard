# Sales & Revenue Analysis Dashboard

## Project Overview

This project is an interactive Power BI dashboard built to analyze sales and revenue performance across products, countries, and time periods.

## Tools Used

- Microsoft Power BI
- DAX
- Excel Dataset

## KPIs

- Total Sales: 118.73M
- Total Profit: 16.89M
- Total Units Sold: 1.13M
- Profit Margin: 14.23%
- Countries Covered: 5

## Dashboard Features

- Sales Analysis by Product
- Profit Analysis by Product
- Country-wise Sales Performance
- Monthly Sales Trend Analysis
- Interactive Country Filter
- KPI Monitoring

## DAX Measures Used

### Profit Margin

```DAX
Profit Margin % =
DIVIDE(
    SUM(financials[Profit]),
    SUM(financials[Sales])
) * 100
```

### Total Countries

```DAX
Total Countries =
DISTINCTCOUNT(financials[Country])
```

## Key Insights

- Paseo was the top-performing product.
- United States generated the highest sales.
- December recorded the highest sales.
- Overall Profit Margin stood at 14.23%.

## Dashboard Screenshot

<img width="1187" height="667" alt="image" src="https://github.com/user-attachments/assets/c4e8b436-e14b-45ce-880d-52fbe6382496" />

