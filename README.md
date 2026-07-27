# Blinkit Grocery Sales & Performance Analytics

## Project Overview
This project delivers an end-to-end exploratory data analysis (EDA) and business intelligence workflow on retail sales data for Blinkit, a quick-commerce grocery platform. The goal was to uncover hidden revenue drivers, evaluate customer preferences across product categories, and analyze outlet performance to derive data-driven recommendations for inventory optimization and sales growth.

---

## Technical Stack & Tools
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

---

## Dataset Summary
* **Total Records:** 8,523 transactions/items
* **Features:** 12 variables including product traits, outlet characteristics, visibility metrics, customer ratings, and total sales.
* **Key Columns:** `Item Fat Content`, `Item Type`, `Item Weight`, `Outlet Size`, `Outlet Location Type`, `Outlet Type`, `Sales`, and `Rating`.

---

## Methodology & Workflow

### 1. Data Cleaning & Preprocessing
* **Text Standardization:** Harmonized categorical discrepancies in `Item Fat Content` (e.g., mapping variant expressions like *"LF"* and *"low fat"* to *"Low Fat"*, and *"reg"* to *"Regular"*).
* **Missing Value Treatment:** Identified and assessed missing entries in `Item Weight` (1,463 missing values) to prepare the feature set for robust aggregations.

### 2. Exploratory Data Analysis (EDA)
* **Revenue Drivers by Category:** Analyzed sales contribution across different product types to identify high-margin and high-volume sectors.
* **Consumer Health Preferences:** Evaluated the market share between Low Fat and Regular product lines across multiple demographic tiers.
* **Outlet Performance Benchmarking:** Compared performance metrics across different outlet establishment years, tier locations, and supermarket store types.

---

## Key Findings & Business Insights

* **Dominance of Health-Conscious Products:** 
  Low Fat items capture approximately **64.6%** of total sales, significantly outperforming Regular items (**35.4%**). This trend holds true across all geographic tiers, indicating a universal consumer shift toward healthier options.
* **Top-Grossing Categories:** 
  Revenue is heavily concentrated in daily essentials. **Fruits and Vegetables** ($178,124) and **Snack Foods** ($175,434) represent the core revenue generators, while niche segments like Seafood and Breakfast yield the lowest turnover.
* **Tier 3 Market Strength:** 
  **Tier 3** outlet locations yield the highest absolute sales volume compared to Tiers 1 and 2, serving as the most lucrative operational zones for inventory allocation.
* **Overall Metrics:**
  The dataset represents a total sales volume of **$1,201,681.50** with an average item rating of **4.0/5.0**.

---

## Strategic Recommendations
1. **Inventory Planning:** Increase stock levels and marketing focus for high-performing, Low-Fat items, particularly in Tier 3 locations where demand is highest.
2. **Category Optimization:** Investigate the low performance of categories like Seafood and Breakfast to determine if the cause is lack of demand, poor visibility, or supply chain issues.
3. **Store Development:** Focus expansion and promotional efforts on Tier 3 environments, which currently serve as the primary revenue drivers.

---

## Repository Structure
```text
├── blinkit_data.csv          # Raw dataset
├── BlinkitDataAnalysis.ipynb # Jupyter Notebook containing full code, EDA, and visualizations
├── README.md                 # Project documentation
└── Comprehensive Blinkit Data Analysis and Strategic Business Report By Varad Sandeep Naik.pdf                 # Project Report
