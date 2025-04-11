# Coffee Shop Sales Dashboard

### 📊 Dashboard Link: https://app.powerbi.com/groups/me/reports/34e05a5a-641b-497a-a0cd-8518b785e3e4/6e783991092001404971?experience=power-bi
### 📊 PDF Link: https://github.com/pd-prachis/Coffee-Shop-Sales-Dashboard/blob/main/Coffee%20Shop%20Sales%20Dashboard.pdf

---

## 📌 Problem Statement

The **Coffee Shop Sales Dashboard** has been developed to assist business stakeholders in understanding key performance metrics across multiple coffee shop branches. It offers actionable insights into revenue, sales volume, and profitability trends—categorized by city, branch, and product type. The dashboard helps decision-makers identify top-performing shops, evaluate customer preferences, and optimize inventory and marketing strategies for maximum business impact.

---

## 🛠️ Steps Followed

1. **Data Loading**: Imported raw sales transaction data (CSV format) into Power BI Desktop.
2. **Data Profiling**: Performed column quality checks using “Column Distribution,” “Column Profile,” and “Column Quality” in Power Query.
3. **Data Transformation**:
   - Replaced nulls and cleaned data inconsistencies.
   - Created date hierarchies for Year and Month.
   - Defined relationships and ensured model optimization.
4. **Visualization Creation**:
   - Added **Card Visuals** to highlight KPIs: *Total Transactions, Total Quantity Sold, Total Revenue, and Total Profit*.
   - Designed **bar charts and column charts** for comparing *Revenue* and *Quantity Sold* across branches, cities, and product categories.
   - Implemented **slicers** for dynamic filtering based on *Year*, *Month*, and *Shop Name*.
5. **DAX Measures Used**:
   - Total Revenue = `SUM(Sales[Revenue])`
   - Total Profit = `SUM(Sales[Profit])`
   - Total Quantity = `SUM(Sales[Quantity])`
   - Total Transactions = `DISTINCTCOUNT(Sales[TransactionID])`
6. **Styling & Publishing**:
   - Chose appropriate color themes to differentiate categories.
   - Used consistent formatting for readability.
   - Published the report to Power BI Service for cloud access and sharing.

---

## 📈 KPI Highlights

- **Total Transactions**: `9,971`
- **Total Quantity Sold**: `14K+`
- **Total Revenue**: `$46.37K`
- **Total Profit**: `$16.23K`

---

## 🔍 Detailed Insights

### 🏪 Shop-Level Performance

- **Top Revenue Branch**: *Central Park* with `$10.9K`
- Other high-performing branches include:
  - *Madison Square* - `$5.8K`
  - *Capitol Hill* - `$5.5K`
  - *Michigan Avenue* - `$5.4K`
- Lowest Revenue: *Zilker Park* and *Hollywood*, contributing under `$3K`.

### 📍 Revenue by City

- **Top Cities by Revenue**:
  - *Chicago* – `$11K`
  - *Los Angeles* – `$11K`
  - *New York* – `$10K`
- Others include *Austin* and *Seattle*, contributing the remaining revenue.

### 📦 Product Category Trends

#### Quantity Sold:

- **Top Selling Categories**:
  - *Desserts* – `7.2K` items
  - *Sandwiches* – `6.76K` items
  - *Tea Beverages* – `6.67K` items
  - *Coffee Beverages* – `6.53K` items
- Other categories include *Specialty Drinks, Snacks,* and *Cold Drinks*.

#### Revenue by Category:

- *Desserts* again lead with **$7.2K revenue** (~15.54% of total).
- Other high revenue categories include:
  - *Sandwiches* – `$6.76K` (~14.57%)
  - *Tea Beverages* – `$6.67K` (~14.39%)
  - *Coffee Beverages* – `$6.53K` (~14.09%)
  - *Specialty Drinks* – `$6.5K` (~14%)
  - *Snacks* – `$6.42K` (~13.85%)
  - *Cold Drinks* – `$6.28K` (~13.55%)

### 🧾 Quantity Sold by Shop Name

- *Suburban Sip Spot*: 892 (6.32%)
- *Brew Cafe*: 868 (6.15%)
- *Perk Café*, *Park Roaste*, *Espresso*, *Hills Cafe* all hover around ~5.9%-6% each.

---

## 💡 Key Takeaways

- **Central Park** branch is the most profitable, contributing the highest revenue and sales volume.
- **Chicago and Los Angeles** outperform all other cities in revenue generation.
- **Desserts and Sandwiches** dominate both in terms of quantity sold and revenue—indicating strong customer preference.
- There is a fairly even distribution of sales across multiple branches, but a few are underperforming and need strategic focus.
- The dashboard provides **dynamic filters** allowing business leaders to compare performance across time periods, shop names, and locations.

---

## 📌 Final Note

This dashboard serves as a comprehensive performance overview of the coffee shop business, enabling informed decision-making related to inventory planning, product bundling, city-level marketing, and sales strategy. All visualizations are interactive and can be filtered dynamically using slicers to drill down into specific shop performances and product category insights.
