# E-Commerce Sales & Profit Analysis Dashboard

This repository contains a sample e-commerce dataset designed for a sales, profit, and customer analysis dashboard.

## Files

- `data/customers.csv` — customer profile and behavior data
- `data/orders.csv` — transaction-level sales and profit dataset

## Dashboard focus areas

- Total sales and profit trends
- Product category performance
- Customer segmentation analysis
- Regional sales comparison
- Repeat customer and churn analysis
- Revenue contribution by customer segment

## Customer dataset fields

- `customer_id`
- `age`
- `gender`
- `region`
- `city`
- `income_range`
- `segment`
- `acquisition_channel`
- `signup_date`
- `total_orders`
- `total_spent`
- `total_profit`
- `avg_order_value`
- `repeat_purchase_rate`
- `churn_risk`
- `is_returning_customer`
- `loyalty_tier`

## Order dataset fields

- `order_id`
- `customer_id`
- `order_date`
- `product_category`
- `product_name`
- `quantity`
- `unit_price`
- `discount_pct`
- `sales_amount`
- `cogs`
- `profit`
- `payment_method`
- `shipping_cost`
- `order_status`
- `region`
- `customer_segment`
- `channel`

## Suggested KPIs

- Total Revenue
- Total Profit
- Profit Margin %
- Average Order Value
- Repeat Customer Rate
- Top Customers by Revenue
- Best-Selling Categories
- Regional Sales Contribution
- Churn Risk Distribution

## Sample usage

Import these files into Excel, Power BI, Tableau, or a Python dashboard and build visualizations such as:

- Sales by month
- Profit by category
- Customer segment performance
- Geographic sales map
- Top 10 customers by profit
- Return vs. repeat purchase analysis
