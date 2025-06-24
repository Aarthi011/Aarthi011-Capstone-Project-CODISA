# Data-Driven Retail Insights: Clustering Sales and Brand Coverage Analysis for Codisa 
A Business Analytics Capstone Project focused on Codisa — a leading Paraguayan distributor — to identify key customer segments and uncover brand expansion opportunities using clustering techniques.

---

## About Codisa

Codisa (Compañía Distribuidora Internacional S.A.) is a top consumer goods distributor in Paraguay with a vast network of clients across food, beverage, and tobacco sectors. The company operates five distribution centers and provides retail services via Codisa Market.

---

## Project Objective

To improve sales performance and portfolio penetration by:
- Identifying high-value customer clusters
- Analyzing sales behavior and brand contribution
- Recommending data-driven strategies to expand brand coverage

---

## Dataset

- Time Period: 13 months
- Clients: 12,913 grocery-type customers
- Products: 192 SKUs in Cigarettes, Food, and Beverages
- Metrics: Sales revenue, brand share, SKU coverage, profitability

---

## Tools Used

- Python: K-means clustering, regression analysis
- Excel: Data cleaning and preprocessing
- Power BI: Dashboard creation and insight visualization

---

## Research Questions

1. How can we increase sales performance by understanding customer segments and purchasing behavior?
2. What strategies can help expand brand coverage across Codisa’s portfolio?
3. How does SKU coverage correlate with profit?

---

## Methodology

- Removed irrelevant sales records (discounts, promotions, asset sales)
- Applied the 80/20 rule to focus on top-selling SKUs
- Performed K-means clustering on product category contribution to sales
- Evaluated cluster quality using Silhouette Score
- Conducted regression analysis to quantify SKU coverage impact on profit

---

## Key Findings

- 5 clusters identified with distinct product preferences
  - Clusters 0–2: Cigarette-dominant (75%+ of sales)
  - Clusters 3–4: Food-dominant, high SKU diversity
- SKU coverage has a strong positive correlation with profitability (R² = 0.57)
- Premium brands like Kent, CANCAO Wine, Nestlé showed high margin but limited coverage in many clusters

---

## Recommendations

- Cluster-Based Marketing:
  - Promote Richester in Cluster 0 (30.39% avg. margin)
  - Launch loyalty programs for premium cigarette brands
  - Bundle offers (e.g., Kent + CANCAO Wine)

- Brand Coverage Expansion:
  - Expand CANCAO Wine and Nestlé SKUs across underperforming clusters
  - Target clients with high margin but low-coverage products

- BI Integration:
  - Centralize classified data into a BI platform for future predictive modeling
  - Include attributes like profit, frequency, and tenure for better segmentation

---

## Limitations & Future Work

- High dimensionality made clustering less interpretable in grocery channel
- Sales-only focus missed other behavioral metrics like frequency or loyalty
- Timeframe limited to 13 months; adding future data may shift cluster patterns

---

## Team Members

- Sai Krishna Chaitanya Srikonda  
- Aarthi Mudiraj Garige  
- Ana Merlo Gonzalez  
- Sarat Buasai  
- Nicolle Fasce  
- Solomiya Sorokotyaha
