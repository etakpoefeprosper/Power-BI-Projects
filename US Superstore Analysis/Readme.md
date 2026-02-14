# US Superstore Sales Analysis Dashboard Report  
**Year-over-Year Performance Review (2023–2024)**  

---
<img width="1009" height="692" alt="image" src="https://github.com/user-attachments/assets/1be421cc-9bc1-406a-aa74-9758d9829151" />

---

**Tools Used:** Microsoft Excel (Data Cleaning, Calculations, Pivot Tables) • Power BI (Interactive Dashboard, DAX Measures, Visualizations)  

---

## Table of Contents

- [Executive Summary](#executive-summary)
- [Data Overview & Methodology](#data-overview--methodology)
- [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
- [Sales Trends & Seasonality](#sales-trends--seasonality)
- [Geographic Performance](#geographic-performance)
- [Product Performance Analysis](#product-performance-analysis)
  - [Revenue by Product](#revenue-by-product)
  - [Quantity Sold by Product](#quantity-sold-by-product)
  - [Discount Impact by Product](#discount-impact-by-product)
- [Key Insights & Observations](#key-insights--observations)
- [Recommendations](#recommendations)
- [Dashboard Screenshots](#dashboard-screenshots)
- [Final Thoughts](#final-thoughts)

---

## Executive Summary

This report analyzes sales performance of a **US Superstore** comparing **2023** vs **2024**, based on an interactive Power BI dashboard.

**Overall Performance (2024 vs 2023):**
- **Revenue** → **$226.2M** (+110.43% YoY)
- **Quantity Sold** → **7M units** (+102.26% YoY)
- **Profit** → **$50M** (+108.85% YoY)
- **Orders** → **~1,000** (+106.87% YoY)
- **Products in Catalog** → 6 (stable)
- **Countries Served** → 5 (stable)

The business experienced explosive double-digit growth across all major metrics in 2024, with particularly strong gains in revenue and profit.

**Top Performing Products (by revenue):** Pencil Colours, Paint Brush, Portraits  
**Highest Discount Exposure:** Pencil Colours (heaviest discounting)  

**Major Insight:** Strong volume growth + aggressive pricing/discount strategy drove massive top-line expansion, while profit growth remained robust despite high discounts on high-volume items.

---

## Data Overview & Methodology

### Data Scope
- Time period: 2023 – 2024  
- Geography: 5 countries (primarily USA, Canada, France, Germany, Mexico)  
- Products: 6 main product lines  
- Metrics: Revenue, Quantity, Profit, Orders, Discounts  

### Methodology
1. **Excel Phase**  
   - Imported raw data  
   - Cleaned inconsistencies in country/product names  
   - Created YoY % change calculations  
   - Built pivot tables for initial category/country breakdowns  

2. **Power BI Phase**  
   - Loaded cleaned Excel model  
   - Created date table and relationships  
   - Wrote DAX measures for:  
     - YoY Growth %  
     - SPLY (Same Period Last Year) comparisons  
     - Running totals & trend lines  
   - Designed single-page executive dashboard with card visuals, line/bar charts, and conditional formatting  

---

## Key Performance Indicators (KPIs)

| Metric              | 2024 Value     | YoY Growth     | SPLY (2023)    | Interpretation                     |
|---------------------|----------------|----------------|----------------|------------------------------------|
| Revenue             | $226.2M        | **+110.43%**   | $107.5M        | Exceptional top-line expansion     |
| Quantity Sold       | 7M units       | **+102.26%**   | 1M units       | Very strong volume growth          |
| Profit              | $50M           | **+108.85%**   | $24.0M         | Profit scaling almost in line      |
| Orders              | ~1,000         | **+106.87%**   | 655            | Healthy order volume increase      |
| Products            | 6              | —              | 6              | Stable assortment                  |
| Countries           | 5              | —              | 5              | No geographic expansion            |

---

## Sales Trends & Seasonality

**Revenue by Month (2024 trend line with marker)**

- Strong seasonal peak in **September** (highest revenue month)  
- Secondary peak visible in **November–December** (likely holiday season buildup)  
- Weakest months: January–March (typical post-holiday slowdown)  
- 2024 shows much higher amplitude compared to 2023 baseline  

**Business implication:** Inventory planning and marketing spend should heavily concentrate in Q3–Q4.

---

## Geographic Performance

**Revenue by Country (2024 – dot plot / bar representation)**

Top revenue-generating markets (descending order):
1. **USA**  
2. **Canada**  
3. **Mexico**  
4. **Germany**  
5. **France**  

**Observation:** North American markets (USA, Canada, Mexico) dominate revenue contribution — international European presence is meaningful but smaller.

---

## Product Performance Analysis

### Revenue by Products (2024)

| Rank | Product          | Revenue     | YoY Growth   |
|------|------------------|-------------|--------------|
| 1    | Pencil Colours   | $87M        | +97.05%      |
| 2    | Paint Brush      | $38M        | +115.08%     |
| 3    | Portraits        | $37M        | +94.36%      |
| 4    | Wood Art Set     | $35M        | +110.34%     |
| 5    | Stapler          | $28M        | +123.41%     |
| 6    | Notebook         | $22M        | +175.84%     |

→ **Notebook** showed the strongest relative growth rate.

### Quantity Sold by Products

- **Pencil Colours** → dominant volume leader (~668K units)  
- **Wood Art Set**, **Paint Brush**, **Portraits** follow in mid-volume tier  
- **Stapler** and **Notebook** lower volume but growing fast  

### Discounts by Products

| Product          | Total Discount Value | Observation                              |
|------------------|----------------------|------------------------------------------|
| Pencil Colours   | $5.7M                | Heaviest absolute discounting            |
| Wood Art Set     | $3.0M                | Significant promotional investment       |
| Paint Brush      | $2.8M                | Moderate-high discounting                |
| Portraits        | $2.7M                | Balanced                                 |
| Stapler          | $2.3M                | Moderate                                 |
| Notebook         | $1.7M                | Lowest discount among top products       |

**Key pattern:** Highest-volume product (Pencil Colours) receives the most aggressive discounting — classic high-low pricing strategy.

---

## Key Insights & Observations

1. **Explosive 2024 Growth**  
   All core KPIs grew >100% YoY — indicates very successful expansion, new customer acquisition, marketing effectiveness, or favorable market conditions.

2. **Seasonality is pronounced**  
   Back-half of the year drives disproportionate revenue — typical for art/supply retail.

3. **Product portfolio performance**  
   - Volume leader (Pencil Colours) is heavily promoted → traffic driver  
   - Fastest growers (Notebook, Stapler) currently lower volume → potential stars  

4. **Geographic concentration**  
   North America accounts for majority of revenue — opportunity to deepen European penetration.

5. **Profit growth almost matches revenue growth**  
   → Discounting has not severely eroded margins in aggregate (very positive signal).

---

## Recommendations

### Short-term (0–6 months)
- **Allocate more budget to Q3–Q4 campaigns** — capitalize on peak season  
- **Test lower discount depth on Pencil Colours** → measure elasticity and margin impact  
- **Accelerate promotion of high-growth items** (Notebook, Stapler) with targeted bundles  

### Medium-term (6–18 months)
- **Expand marketing in France & Germany** — test localized campaigns  
- **Introduce 1–2 new premium art products** to capture higher-margin segment  
- **Build customer loyalty program** focused on repeat art-supply purchasers  

### Long-term
- **Monitor discount-to-profit correlation monthly** — set threshold alerts  
- **Explore adjacent categories** (e.g. canvases, easels, digital art tools)  

---

## Dashboard Screenshots

**Main Dashboard – US Superstore Sales Overview (2023–2024)**  

![US Superstore Sales Dashboard](<img width="1009" height="692" alt="image" src="https://github.com/user-attachments/assets/1be421cc-9bc1-406a-aa74-9758d9829151" />)  

---

## Final Thoughts

2024 was a breakout year for the US Superstore — more than doubling revenue, units, and profit while maintaining healthy margin progression.

The current strategy of **high-volume traffic drivers + seasonal focus + aggressive but controlled discounting** appears to be working exceptionally well.

Continued disciplined execution + selective international and product-line expansion could position the business for sustained multi-year growth.

**Data → Insight → Action → Results**

---
