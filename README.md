# Tableau Project: Analyzing Sales Trends and Patterns

This Tableau project aims to analyze sales data from various dimensions including product, customer, promotion, and currency. The dashboard consists of five main sheets: Overview, PRODUCT, CUSTOMER, PROMOTION, and CURRENCY. Each sheet provides insights into different aspects of the sales data, facilitating better decision-making and understanding of customer behavior and product performance.

---

## Description 
### Dashboard Snapshot
<div>
   <img src="https://github.com/sarax0/sales-analysis-tableau/assets/122404545/32962488-71a8-4ccd-ac9a-a41547351a57" alt="Description of the image" width="45%">
   <img src="https://github.com/sarax0/sales-analysis-tableau/assets/122404545/518e140c-1f07-47fd-be99-7634041ef582" alt="Description of the image" width="45%">
</div>


### Dashboard Link
[Link to Tableau Dashboard](https://public.tableau.com/views/InternetSales2019Tableua/InternetSales?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

### Overview Sheet
The Overview sheet serves as the landing sheet of the dashboard, providing a high-level summary of key metrics and insights derived from the sales data. It offers an executive summary of the project, highlighting important trends and findings.

### PRODUCT Sheet
The PRODUCT sheet focuses on detailed analysis related to product sales. It provides insights into product performance, including total sales, profit margins, and top-selling products. Users can explore sales data by various product attributes such as category, sub-category, and brand.

### CUSTOMER Sheet
The CUSTOMER sheet delves into customer-centric analysis, offering insights into customer behavior and preferences. It includes metrics such as total orders per customer, total profit generated by customers, and top purchasing customers. This sheet helps in understanding customer segments and tailoring marketing strategies accordingly.

### PROMOTION Sheet
The PROMOTION sheet explores the effectiveness of promotional activities on sales performance. It analyzes the impact of different promotional campaigns on revenue generation and customer engagement. Users can visualize promotional trends over time and identify which promotions yield the highest returns.

### CURRENCY Sheet
The CURRENCY sheet provides analysis related to currency fluctuations and their impact on sales. It includes visualizations depicting sales trends in different currencies, exchange rate variations, and their influence on revenue and profitability. This sheet assists in understanding the global sales landscape and managing currency-related risks.

---

## Implemented Requirements

1. **Identifying Age Group with Highest Purchase**
   - Utilized sales data to determine which age group makes the most purchases.
2. **Analysis of Freight, Tax, Sales Amount, and Cost**
   - Examined freight, tax, sales amount, and cost to understand their impact on overall profitability.
3. **Product Sales Analysis**
   - Analyzed product sales on a monthly and yearly basis.
4. **Profit vs. Orders Count Over Time**
   - Visualized the relationship between profit and orders count over time to identify trends.
5. **Top Sales Sub-Product**
   - Implemented a parameter-driven filter to identify top-selling sub-products by quantity.
6. **Mapping Top Selling Products**
   - Utilized mapping visualization to showcase the geographical distribution of top-selling products.
7. **Revenue Calculation**
   - Calculated revenue using the formula: `Revenue = RetailPrice * OrderQuantity`.
8. **Total Cost Calculation**
   - Determined total cost using the formula: `Total Cost = SUMX(OrderQuantity * ProductCost)`.
9. **Total Returns and Orders Analysis**
   - Analyzed total returns and total orders to evaluate customer behavior.
10. **Number of Products**
    - Calculated the total number of unique products.
11. **Total Profit Calculation**
    - Computed total profit using the formula: `Total Profit = Total Revenue - Total Cost`.
12. **Customer Analysis**
    - Analyzed customer data including total orders, total profit, and top purchases.
13. **Product Analysis**
    - Analyzed product data including total orders, total profit, and top sales.
14. **Gender-Based Revenue and Orders Analysis**
    - Analyzed revenue and orders based on gender to understand gender preferences.
15. **Age-Based Daily Purchases**
    - Analyzed age-based daily purchases to identify purchasing patterns.
