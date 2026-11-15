# Cafe Sales Data Analysis

## 1. Project Overview

This project focuses on analysing cafe sales data to uncover meaningful patterns in sales performance, product preferences, customer purchasing behaviour, and payment methods.

The project follows a complete data analysis workflow, starting with raw data inspection and cleaning, followed by Exploratory Data Analysis (EDA) and business insight generation. A Power BI dashboard will also be developed to present key findings through interactive visualisations.

## 2. Project Objectives

- Clean and prepare raw cafe sales data for analysis.
- Analyse overall sales and revenue patterns.
- Identify top-performing products based on sales volume and revenue.
- Examine customer purchasing behaviour across different payment methods.
- Compare sales performance across service types.
- Explore monthly and weekly sales trends.
- Generate meaningful, data-driven business insights.
- Present key findings through a Power BI dashboard.

## 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Jupyter Notebook | Analysis environment |
| Power BI | Interactive dashboard development |

## 4. Data Cleaning & Preparation

The raw cafe sales dataset was inspected and processed using Python.

This stage focused on preparing the dataset for reliable analysis and producing a cleaned dataset for subsequent EDA.

The cleaned dataset was saved separately from the original raw data.

**Notebook:** `Cafe_sales_analysis.ipynb`

## 5. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed using Python to understand the dataset and identify patterns across different business dimensions.

The analysis was organised into the following sections:

- Overview
- Product Analysis
- Payment Method Analysis
- Univariate Analysis
- Time-Based Analysis
- Service-Type Analysis

The analysis included descriptive statistics, category-based comparisons, transaction distributions, and visualisations.

**Notebook:** `Cafe_Sales_EDA.ipynb`

## 6. Business Findings

### 6.1 Product Analysis

- **Product Sales Volume:** Coffee recorded the highest sales volume with 3,904 units, followed by Salad (3,819 units). Smoothie recorded the lowest sales volume at 3,336 units.
- **Product Transaction Frequency:** Coffee appeared in the highest number of transactions (1,286), followed by Salad (1,270). Smoothie had the lowest transaction frequency (1,094).
- **Average Spending and Unit Price:** Salad had the highest average transaction spending at ₹15.04 and the highest average selling price at ₹5.00 per unit. Cookie recorded the lowest average transaction spending (₹2.97) and the lowest average selling price (₹1.00).
- **Monthly Product Revenue:** Salad consistently generated the highest revenue among known products across all 12 months. Its revenue peaked in July at ₹1,715 and was lowest in September at ₹1,245.

### 6.2 Payment Method Analysis

- **Average Transaction Value:** Cash transactions had the highest average transaction value at ₹9.05, followed by Credit Card (₹9.01) and Digital Wallet (₹8.93).
- **Total Revenue:** Credit Card generated the highest revenue at ₹20,446, followed by Digital Wallet (₹20,405) and Cash (₹20,402.50).
- **Overall Payment Performance:** Credit Card led in total revenue, Digital Wallet recorded the highest transaction count (2,284), and Cash had the highest average transaction value. Revenue differences across payment methods were relatively small.
- **Purchase Quantity:** The median purchase quantity was 3 units across all three payment methods. Average quantities were also similar, indicating relatively consistent purchase quantities regardless of payment method.

### 6.3 Customer and Transaction Behaviour

- **Transaction Amount Distribution:** The dataset contained 9,974 transactions, with an average transaction value of ₹8.93 and a median of ₹8. Transaction amounts ranged from ₹1 to ₹25. The middle 50% of transactions fell between ₹4 and ₹12. The most frequent transaction amount was ₹6 (1,019 transactions), followed by ₹12 (996 transactions).
- **Purchase Quantity Distribution:** The average purchase quantity was approximately 3.02 units, with a median of 3 units. Purchases of 5 units were most frequent (2,006 transactions), while purchases of 3 units were least frequent (1,841 transactions).
- **Weekly Transaction Distribution:** Friday recorded the highest transaction count (1,383), while Tuesday recorded the lowest (1,308). The difference was 75 transactions.
- **Service-Type Transaction Distribution:** Among transactions with known location data, Takeaway recorded 3,016 transactions, compared to 3,006 for In-store. The difference was only 10 transactions, indicating nearly equal usage of both service types.

### 6.4 Time-Based Analysis

- **Monthly Revenue:** June generated the highest monthly revenue at ₹7,353, followed by October (₹7,314). February recorded the lowest revenue at ₹6,644. The difference was ₹709, with no consistent upward or downward trend observed.
- **Weekday Revenue:** Thursday generated the highest revenue at ₹12,401.50, followed by Friday (₹12,334). Wednesday recorded the lowest revenue at ₹11,671.50. The difference was ₹730.
- **Monthly Average Transaction Value:** April recorded the highest average transaction value at approximately ₹9.31, followed by February (₹9.15). July had the lowest average at approximately ₹8.72.
- **Weekday Average Transaction Value:** Tuesday recorded the highest average transaction value at approximately ₹9.20, while Wednesday had the lowest at approximately ₹8.72. Thursday generated the highest total weekday revenue but ranked second in average transaction value.
- **Monthly Transaction Volume:** October recorded the highest transaction volume (837), followed by March (826). February had the lowest volume (726), a difference of 111 transactions.
- **Transaction Volume vs. Revenue:** Higher transaction volume did not always correspond to higher revenue. October recorded 837 transactions and generated ₹7,314, while June generated higher revenue of ₹7,353 with only 817 transactions. March recorded 826 transactions and generated ₹7,216.
- **Average Daily Revenue:** June recorded the highest average daily revenue at approximately ₹245.10, followed by April (₹239.30). July had the lowest average daily revenue at approximately ₹221.85.
- **Average Purchase Quantity by Month:** February had the highest average purchase quantity at approximately 3.09 units, followed by December (3.07). July recorded the lowest average at approximately 2.95 units.

### 6.5 Service-Type Analysis

- **Total Revenue by Service Type:** In-store generated the highest total revenue at ₹27,140, compared to Takeaway at ₹26,552.50. The difference was ₹587.50.
- **Average Transaction Value by Service Type:** In-store orders had a slightly higher average transaction value (₹9.03) than Takeaway orders (₹8.80), a difference of approximately ₹0.22.

## 7. Power BI Dashboard

[Dashboard screenshots, KPIs and key visualisations will be added after dashboard development.]

## 8. Conclusion

[Final business conclusions will be added after completing the dashboard and reviewing the overall project.]

## 9. Dataset & Credits

[Dataset source, creator attribution and applicable dataset license details will be added here.]

## 10. License

[Project code license details will be added here.]
