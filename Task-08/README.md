# Business Category Analysis Using Tree Map in Tableau

Link : https://public.tableau.com/views/BusinessCategorySalesPerformanceDashboard/BusinessCategorySalesPerformanceDashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Objective

Analyze the contribution of different business categories using a Tree Map in Tableau and identify the categories and sub-categories that have the greatest impact on business performance.

## Dataset

The **Superstore Sales Dataset** was selected from Kaggle.

The dataset contains business information such as:

* Category
* Sub-Category
* Sales
* Profit
* Quantity
* Order Date
* Region
* Segment

## Tools Used

* Tableau Public
* Kaggle Dataset

## Tree Map Analysis

A Tree Map was created to compare the contribution of different product categories and sub-categories.

### Tree Map Configuration

* **Size:** SUM(Sales)
* **Color:** SUM(Profit)
* **Label:** Sub-Category
* **Category:** Category

The size of each block represents the sales contribution of the sub-category. The colour indicates the profitability of each sub-category.

## Additional Visualizations

Three additional visualizations were created:

### 1. Sales by Category

A bar chart was created to compare total sales between different categories.

### 2. Sales Trend Over Time

A line chart was created to analyze how sales changed over the selected time period.

### 3. Sales by Region

A chart was created to compare business performance across different regions.

## Dashboard

All visualizations were combined into a single interactive Tableau dashboard.

The dashboard provides a consolidated view of:

* Category contribution
* Sub-category performance
* Sales trends
* Regional performance
* Profitability

## Business Insights

1. Technology-related products contribute significantly to overall sales and represent an important category for the business.

2. Furniture contributes a large amount of sales, but some furniture sub-categories have comparatively lower profitability.

3. Office Supplies provide a consistent contribution to the overall business performance.

4. Some products generate high sales but relatively low profit, indicating that pricing, discounts, or operating costs may need to be reviewed.

5. Business performance differs between regions, showing that some geographical markets contribute more strongly than others.

## Business Recommendations

### Recommendation 1: Focus on High-Profit Products

The company should increase inventory availability and marketing efforts for sub-categories that generate both high sales and high profit.

### Recommendation 2: Improve Low-Profit Products

Products with high sales but low profitability should be reviewed. The company can evaluate pricing, discounts, supplier costs, and operating expenses to improve profit margins.

## Conclusion

The Tableau dashboard provides a clear visual representation of business category performance. The Tree Map makes it easy to identify the categories and sub-categories contributing the most to sales, while the additional visualizations provide insights into sales trends and regional performance.

This analysis can help management make better decisions regarding product focus, inventory planning, pricing, and marketing strategies.
