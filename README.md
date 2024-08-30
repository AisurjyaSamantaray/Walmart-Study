# Walmart Sales Analysis Project

This project analyzes weekly sales data from Walmart stores to uncover key insights and relationships between variables. The following key areas were addressed:

- Investigate sales performance across various stores over the years.
- Examining the influence of temperature and fuel prices on sales.
- Performing hypothesis testing to assess the impact of promotional campaigns on sales.
- Visualizing trends in sales and other relevant factors to make informed conclusions.

## Dataset Description

The Walmart dataset contains the following columns:

| Column Name      | Description                                                      |
|------------------|------------------------------------------------------------------|
| `Store`          | Identifier for the store.                                        |
| `Date`           | Date of the weekly sales data.                                   |
| `Weekly_Sales`   | Total weekly sales for each store.                               |
| `Temperature`    | Temperature at the store's location during the week.             |
| `Fuel_Price`     | Fuel price in the region of the store.                           |
| `CPI`            | Consumer Price Index (CPI) for the store's region.               |
| `Unemployment`   | Unemployment rate in the region where the store is located.      |
| `Holiday_Flag`   | Indicator (1 if a special holiday occurred during the week, 0 otherwise). |

## Key Analyses and Results

1. **Sales Performance by Store and Year**:
   - Significant variations in weekly sales across different stores and years.
   - Some stores showed a consistent increase in sales year-over-year, while others fluctuated.

2. **Impact of Temperature on Sales**:
   - Weak correlation between temperature and sales, indicating limited influence.
   - Sales appeared relatively stable across various temperature ranges.

3. **Hypothesis Testing on Promotional Impact**:
   - The t-test revealed a statistically significant difference in sales before and after the promotion.
   - Promotional campaigns led to a noticeable increase in sales for most stores.

4. **Relationship Between Fuel Prices and Sales**:
   - Sales fluctuated slightly with changes in fuel prices, though no strong correlation was observed.
   - Higher fuel prices did not significantly dampen sales, suggesting consumer resilience.
