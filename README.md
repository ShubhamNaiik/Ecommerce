# Ecommerce Sales and Performance Dashboard

## Project Overview
This project analyzes sales data across various customer segments, regions, and product categories. Using an interactive Excel dashboard, the analysis provides key insights into sales performance, profit margins, order quantities, and customer demographics to guide decision-making for businesses looking to optimize their sales strategies.

## Objectives
- **Sales Performance Analysis**: Evaluate sales and profit margins across regions and product categories.
- **Customer Segmentation**: Understand customer demographics and behavior for targeted marketing.
- **Product Performance**: Analyze top-selling products and order quantities by market.
- **Market Trends**: Track trends in order volume, sales, and profits over time.
- **Operational Insights**: Explore shipping modes, order statuses, and their impact on sales.

## Dashboard 
![image](https://github.com/user-attachments/assets/af961ee3-b461-4977-b8da-cc1121c66114)


## Dataset Description
The project uses sales transaction data with the following key columns:

| Column Name             | Description                            |
|-------------------------|----------------------------------------|
| Customer ID             | Unique identifier for each customer    |
| Customer City, State    | Customer's geographical location       |
| Customer Segment        | The customer type (e.g., Consumer)     |
| Order Date              | Date when the order was placed         |
| Product Category        | Category of the product purchased      |
| Product Price           | Price of the product                   |
| Order Quantity          | Number of products in the order        |
| Sales                   | Total sales amount for the order       |
| Profit Margin           | Profit margin for the order            |
| Profit Per Order        | Profit earned from the order           |
| Shipping Mode           | Type of shipping selected              |
| Order Status            | Status of the order (e.g., Complete)   |

## Data Preparation
- Cleaned the dataset to standardize column formats.
- Used Excel functions like `SUMIFS`, `AVERAGEIFS`, and `COUNTIF` to calculate key metrics such as total sales, average profit, and number of orders.
- Created PivotTables and PivotCharts to summarize and filter data.
- Developed slicers for user interaction to explore different metrics by customer segment, region, or time period.

## Dashboard Features
- **KPI Cards**: Displayed total sales, profit margin, and average order quantity for quick insights.
- **Sales by Region**: A map view showing total sales in different regions and countries.
- **Product Performance**: Ranking of top-selling products and categories by sales.
- **Profit Margin Trends**: Line chart tracking profit margins over time.
- **Customer Segmentation**: Bar charts illustrating sales and profit by customer type.
- **Shipping Mode Impact**: Analysis of how shipping modes influence sales.

## Key Insights
1. **Sales Growth by Region**:
   - The Europe region has shown the highest growth in sales, with the largest contribution coming from countries like **Francia** and **Germany**. This suggests that the business should prioritize expansion efforts in these regions.

![image](https://github.com/user-attachments/assets/611c6d4d-dcfb-4b85-9dbd-6fc848f193ba)


2. **Top-Selling Product Categories**:
   - The **Cardio Equipment** category consistently generates the highest sales, with a **10% growth** year-over-year.

![image](https://github.com/user-attachments/assets/536233bd-a5fd-4e67-a31d-cdb5122ba105)


3. **Customer Segment Performance**:
   - **Consumers** make up **75%** of all orders, but **Business Clients** contribute higher average sales per order.

4. **Profit Margin Analysis**:
   - Products from the **Sporting Goods** category exhibit the highest profit margins at **18%**, whereas the **Strenght Training** category shows negative profit margins.

5. **Shipping Mode Effectiveness**:
   - **Standard Class** is the most commonly selected shipping mode, but **Same Day** has shown a higher profit margin per order.

## Recommendations
- **For Sales Teams**:
  - Focus on expanding into high-growth regions like LATAM and Europe.
  - Promote top-selling product categories (e.g., Cardio Equipment) through targeted marketing campaigns.

- **For Marketing Teams**:
  - Segment marketing efforts based on customer type (Consumer vs. Business Clients) and geographic location to maximize engagement.

- **For Operations Teams**:
  - Analyze shipping modes like **First Class** and **Second Class** and optimize fulfillment processes to support faster shipping options, improving customer satisfaction and profit margins.

## Conclusion
This analysis provides valuable insights into ecommerce sales performance across multiple regions and product categories. By leveraging data-driven strategies, businesses can better target their resources, optimize their product offerings, and improve overall sales and profitability.



