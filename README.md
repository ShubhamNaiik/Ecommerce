# Ecommerce

##  Introduction 
<img width="1280" alt="Image" src="https://github.com/user-attachments/assets/688d145e-bedc-4e87-97fc-204edff952b4" />

This project analyzes e-commerce transaction data to evaluate sales performance, regional trends, product category insights, and customer segments. The purpose is to derive business intelligence from historical sales and optimize marketing, logistics, and inventory decisions.

##  Objective  
The objective of this dashboard is to identify high-performing products, regions with the most revenue, customer buying behaviors, and factors affecting profit margins. The analysis enables data-driven decision-making for growth strategies.

##  Dataset Overview  

| Column Name          | Data Type         | Description                            |
|----------------------|-------------------|----------------------------------------|
| `Category Name`      | object            | Additional attribute                   |
| `Customer City`      | object            | Additional attribute                   |
| `Customer Fname`     | object            | Additional attribute                   |
| `Customer Id`        | int64             | Additional attribute                   |
| `Customer Segment`   | object            | Additional attribute                   |
| `Customer State`     | object            | Additional attribute                   |
| `Customer Zipcode`   | int64             | Additional attribute                   |
| `Market`             | object            | Additional attribute                   |
| `Order Customer Id`  | int64             | Additional attribute                   |
| `Order Date`         | datetime64[ns]    | Date when the order was placed         |
| `Order Id`           | int64             | Additional attribute                   |
| `Order Region`       | object            | Additional attribute                   |
| `Order Item Total`   | float64           | Additional attribute                   |
| `Order Quantity`     | int64             | Additional attribute                   |
| `Product Price`      | float64           | Additional attribute                   |
| `Profit Margin`      | float64           | Additional attribute                   |
| `Profit Per Order`   | float64           | Additional attribute                   |
| `Sales`              | float64           | Sales revenue from the order           |
| `Order Country`      | object            | Additional attribute                   |
| `Order Status`       | object            | Additional attribute                   |
| `Shipping Mode`      | object            | Additional attribute                   |

##  Key Findings  
- **Technology** is the top-performing category in both sales and profit
- The **West and East regions** contribute the most to overall revenue
  <img width="643" alt="Image" src="https://github.com/user-attachments/assets/ecc465fa-af26-4119-925d-7487bcd54108" />
   
- Customers from the **Consumer segment** generate the highest order volume
  <img width="563" alt="Image" src="https://github.com/user-attachments/assets/27e5dd7c-f36a-4e7f-af4f-f404fec19522" />
  
- Higher discounts tend to reduce profitability in certain product categories  
- Top-performing cities include **New York, Los Angeles, and Seattle**  

##  Recommendations  
1. Focus **marketing efforts** on high-revenue regions and top customer segments
2. Reassess **discount strategies** to avoid profit loss in specific categories
3. **Stock more inventory** for high-demand items from top-performing sub-categories
4. Introduce **loyalty programs** targeting the Consumer segment to boost retention  

##  Conclusion  
This dashboard provides actionable insights for sales optimization, product strategy, and customer engagement.By continuously monitoring sales trends
