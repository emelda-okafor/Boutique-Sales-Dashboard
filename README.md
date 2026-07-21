# Boutique Store Sales Analysis

Analysis of a full year of transactional sales data for a boutique fashion retailer operating across five Nigerian cities — built to surface where revenue and profit are actually coming from, and where they're leaking.

## Project Overview

The dataset covers 300 individual orders placed between January and December 2025, spanning five product categories, five cities, and three payment methods. Beyond the raw transaction log, the workbook includes pre-built pivot summaries so the key breakdowns are ready to explore immediately.

## Key Insights

- **₦11.3M in total sales generated ₦3.7M in profit** — a ~33% margin across the year
- **Shoes is the top-performing category** (₦3.6M in sales), driven largely by Heels and Sneakers
- **Enugu outperforms every other city** (₦2.6M), narrowly ahead of Abuja — worth investigating what's driving that gap
- **December is the strongest month** (₦1.4M), suggesting a seasonal/holiday sales lift worth planning inventory around
- **Payment methods are evenly split** between Cash, POS, and Transfer — no single channel dominates, which has implications for reconciliation and cash-flow planning

## Recommendations

- **Double down on Shoes** — it's the top-grossing category; consider expanding SKU variety (colors/sizes) for Heels and Sneakers specifically, since they drive the bulk of that category's revenue
- **Investigate what's working in Enugu** — its outperformance over cities like Lagos and Ibadan may point to a stronger sales team, better local marketing, or product-mix fit worth replicating elsewhere
- **Plan inventory and staffing around the December peak** — stock up on top sellers ahead of the holiday season rather than reacting to demand in real time
- **Review discounting strategy** — with a ~33% overall margin, it's worth checking whether heavy discounts on lower-margin items are eating into profit without meaningfully lifting volume
- **Keep supporting all three payment methods** — since none dominates, cutting one (e.g. to reduce reconciliation overhead) risks alienating a meaningful share of customers

## Dataset Structure

**`Boutique_Store_Sales_Dataset.xlsx`** contains:

| Sheet | Contents |
|---|---|
| Cleaned Data | 300 orders × 18 columns — the full transaction log |
| Pivot sheets | Pre-aggregated views by category, city, product, month, and payment method |

**Columns in Cleaned Data:** Order ID, Order Date, Customer Name, Gender, Age, City, Product Category, Product, Size, Color, Quantity, Unit Price, Discount (%), Sales, Cost, Profit, Payment Method, Salesperson.

## Tools & Skills Demonstrated

- Data cleaning and structuring
- Pivot table analysis
- Sales, profit, and margin analysis
- Trend analysis across time, geography, and category
- Excel-based reporting (adaptable to Power BI / Tableau / pandas)

## Possible Next Steps

- Build an interactive dashboard (Power BI / Tableau) on top of this data
- Segment customers by age, gender, and city to inform targeted promotions
- Model discount impact on margin to find the optimal discount range

## License

MIT — free to use, adapt, and build on.

---
*Note: this is a synthetic dataset created for portfolio/practice purposes and does not represent a real business.*
