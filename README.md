# Sales_Analysis


## Introduction:

The "Global_Superstore_2016.xlsx" dataset contains information on orders placed across different countries, regions, and markets, including details about products, sales, profits, customers, and shipping. This analysis provides valuable insights into the performance of the business, customer behavior, and product profitability using Power BI. The report includes key KPIs such as sales performance, delivery times, and profit trends.

### Dataset Description:

The dataset includes the following columns:

- Row ID: Unique identifier for each record in the dataset.
- Order ID: Unique identifier for each order.
- Order Date: Date the order was placed.
- Ship Date: Date the order was shipped.
- Ship Mode: The mode of shipping (e.g., Standard Class, First Class).
- Customer ID: Unique identifier for each customer.
- Customer Name: Name of the customer.
- Segment: The business segment (e.g., Consumer, Corporate, Home Office).
- Postal Code: The postal code of the customer.
- City: The city of the customer.
- State: The state of the customer.
- Country: The country of the customer.
- Region: The region of the customer (e.g., East, West).
- Market: The market the customer belongs to.
- Product ID: Unique identifier for the product.
- Category: The category of the product (e.g., Furniture, Technology).
- Sub-Category: The sub-category of the product.
- Product Name: The name of the product.
- Sales: The sales amount for the order.
- Quantity: The quantity of products sold.
- Discount: The discount given on the order.
- Profit: The profit earned from the order.
- Shipping Cost: The cost of shipping the order.
- Order Priority: The priority of the order (e.g., High, Medium, Low).

### KPIs (Key Performance Indicators):

1. Total Sales:
Sum of the sales amount for all orders.
Used to track overall revenue performance.
 
2. Total Quantity Sold:
Sum of the quantity of products sold.
Helps analyze product demand and market performance.
 
3. Average Delivery Days:
Calculated by subtracting the order date from the ship date.
Shows the average time taken to deliver orders.

4. Returned Orders:
Analysis of orders that were returned (if return data is available).
This KPI helps identify customer satisfaction and product return rates.

5. Sales by Segment:
Sales broken down by different customer segments (e.g., Consumer, Corporate, Home Office).
Helps identify which segments contribute most to revenue.

6. Top 10 Customers:
A list of the top 10 customers based on sales amount.
Identifies the most valuable customers for targeted marketing.

7. Top 6 Loss-Making Products:
A list of the top 6 products with the highest losses (calculated as low profit or negative profit).
Helps understand which products may need pricing or sales strategy adjustments.

8. Top 6 Profit-Making Products:
A list of the top 6 products that generate the most profit.
These are the most valuable products in terms of profitability.

9. Sum of Quantity by Region:
Total quantity of products sold, broken down by region.
Helps identify which regions are performing well and where there may be growth opportunities.
Steps for Power BI Sales Analysis:


### Data Import:

Import the Global Superstore dataset into Power BI.
Ensure the data types for each column are correctly assigned (e.g., date fields, numeric fields).
Data Cleaning and Transformation:

Ensure that the order and ship dates are in the correct format.
Create calculated columns for KPIs such as "Delivery Days" by subtracting the order date from the ship date.

### Visualization Creation:

- Sales Overview: Create a bar chart or line graph to show the total sales over time.
- Quantity Sold: Visualize the quantity of products sold using a bar chart or pie chart.
- Average Delivery Days: Use a KPI card to display the average delivery time.
- Returned Orders: If return data is available, show a table or chart of orders that were returned.
- Sales by Segment: Create a pie chart or bar graph to visualize sales contribution by segment.
- Top 10 Customers: Use a table or bar chart to display the top 10 customers by sales.
- Top 6 Loss-Making Products: Use a table or bar chart to show the products with the most loss.
- Top 6 Profit-Making Products: Highlight the most profitable products using a similar visual.
- Sales by Region: Display regional sales using a map or a bar chart.


### Dashboard Creation:

Combine all the visualizations into a dashboard to provide an at-a-glance overview of the sales performance, top customers, and product performance.

### Conclusion:
This analysis provides key insights into sales performance, customer segmentation, product profitability, and shipping efficiency. By using Power BI, you can dynamically explore the dataset, drill down into details, and make data-driven decisions to improve sales strategies and operations.

### How to Use:
Open the Power BI file.
Navigate between the different reports using the dashboard view.
Filter data by region, segment, or product categories to gain specific insights.
