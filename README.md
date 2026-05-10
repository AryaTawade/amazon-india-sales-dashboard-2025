# Amazon India Sales Dashboard 2025

An interactive, single-file sales analytics dashboard for Amazon India FY 2025 data, built with vanilla HTML, CSS, and Chart.js. No frameworks, no dependencies, no server required — just open the file in a browser.

## Preview

The dashboard covers six key sections:

- **KPI Cards** — Total revenue, orders, average order value, and high-value order count
- **Monthly Revenue Trend** — Line chart across all 12 months of 2025
- **Category Breakdown** — Revenue comparison across Beauty, Electronics, Books, Clothing, and Home & Kitchen
- **Payments, Delivery & Returns** — Payment method splits, delivery status donut, and return rates by category
- **Top Products & Regional Sales** — Top 10 products by revenue and state-wise sales bar chart
- **Customer Insights** — Top states by customer count and highest repeat buyers

## Data Summary

| Metric | Value |
|---|---|
| Total Revenue | ₹118.2 Cr |
| Total Orders | 15,000 |
| Avg Order Value | ₹74,544 |
| High-Value Orders (> ₹1L) | 4,291 |
| States Covered | 28 |
| Product Categories | 5 |

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/amazon-india-sales-dashboard-2025.git
   ```

2. Open the dashboard
   ```bash
   cd amazon-india-sales-dashboard-2025
   open amazon_dashboard_2025.html
   ```

No install step needed. Works in any modern browser.

## File Structure

```
amazon-india-sales-dashboard-2025/
├── amazon_dashboard_2025.html   # Main dashboard (self-contained)
├── amazon_sales_2025_INR_cleaned.csv  # Source data
└── README.md
```

## Tech Stack

- HTML5 & CSS3
- [Chart.js 4.4.1](https://www.chartjs.org/) via CDN
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts

## Data Source

Aggregated Amazon India sales data for FY 2025, denominated in Indian Rupees (INR). The CSV contains pre-aggregated report sections including monthly trends, category performance, state-wise sales, customer frequency, payment preferences, and return rates.

## License

MIT
