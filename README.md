# Transaction Analysis Dashboard

## Overview

This project involves the creation of a comprehensive dashboard to analyze transaction data across three different store locations. The dashboard is designed to provide stakeholders with valuable insights into various metrics, including revenue, transaction patterns, and product performance.

## Dataset Description

The dataset used in this project contains detailed transaction information. Below are the columns included in the dataset:

| Column              | Description                            |
|---------------------|----------------------------------------|
| transaction_id      | Unique identifier for each transaction |
| transaction_date    | Date of the transaction                |
| transaction_time    | Time of the transaction                |
| transaction_qty     | Quantity of items in the transaction   |
| store_id            | Identifier for the store location      |
| store_location      | Name of the store location             |
| product_id          | Identifier for the product             |
| unit_price          | Price per unit of the product          |
| product_category    | Category of the product                |
| product_type        | Type of product                        |
| product_detail      | Detailed description of the product    |
| revenue             | Revenue generated from the transaction |
| Month               | Month of the transaction               |
| Month Name          | Name of the month                      |
| Weekday             | Day of the week (numeric)              |
| Weekday Name        | Name of the weekday                    |
| Hour                | Hour of the day (24-hour format)       |

## Dashboard Features

The dashboard includes the following features to help stakeholders gain valuable insights:

1. **Revenue by Month**: Displays total revenue generated each month.
2. **Transactions by Day of the Week**: Analyzes transaction frequency for each day of the week.
3. **Transactions by Time of Day**: Shows the distribution of transactions across different hours of the day.
4. **Transactions by Product Category**: Provides a breakdown of transactions based on product categories.
5. **Top 15 Products**: Highlights the top 15 products based on the number of transactions.

### Interactive Slicer

- **Location Slicer**: Allows users to filter the data by store location. The dashboard dynamically updates to reflect the selected location.

## Purpose

This project aims to:

- **Identify Revenue Trends**: By analyzing revenue patterns across different months, stakeholders can identify peak sales periods and strategize accordingly.
- **Optimize Store Operations**: Understanding transaction patterns by day and time helps optimize staffing and inventory management.
- **Enhance Product Offerings**: Insights into product categories and top-performing products guide decisions on product stocking and promotional efforts.
- **Tailor Strategies by Location**: The ability to filter data by location allows for location-specific strategies to maximize performance.

## Recommendations

Based on the analysis of the data, here are some recommendations:

1. **Optimize Store Hours**: The bulk of transactions occur between the hours of 7 AM and 10 AM. To reduce costs, consider reducing store hours later in the day when transactions are lower.
2. **Promote Food Products**: Beverages make up the bulk of our sales. We could run promotional deals to boost sales of food products that are in our top 15 but still have lower transaction and revenue volumes compared to beverages.
3. **Evaluate Product Line**: Packaged chocolate is a low seller across all locations. Assess if it's necessary to keep this product line or if it should be replaced with more popular items.
4. **Enhance Customer Experience**: Based on peak transaction times, ensure adequate staffing and resources during these hours to maintain high service quality and reduce customer wait times.

## Next Steps

To build on these insights and make more informed decisions, consider gathering and analyzing additional data:

1. **Customer Wait Times**:
   - Measure and analyze customer wait times during different hours and days to identify peak times and potential bottlenecks.

2. **Customer Satisfaction**:
   - Collect customer satisfaction data through surveys or feedback forms to gauge customer experience and identify areas for improvement.

3. **Employee Performance**:
   - Track employee performance metrics such as sales per hour, customer interactions, and upselling success to identify training needs and top performers.

4. **Inventory Levels**:
   - Monitor inventory levels in real-time to ensure popular products are always in stock and reduce the risk of overstocking low-selling items.

5. **Promotion Effectiveness**:
   - Analyze the effectiveness of different promotions and discounts to determine which strategies drive the most sales and revenue.

6. **Competitor Analysis**:
   - Conduct a competitor analysis to understand market trends and identify opportunities to differentiate and capture more market share.

## Technical Implementation

### Tools Used

- **Data Source**: CSV file containing transaction data
- **Data Processing**: Microsoft Excel to transform data.
- **Dashboard Creation**: Microsoft Excel to create the interactive dashboard.

### Steps Taken

1. **Data Transformation**: Calculated additional fields such as `Revenue`, `Month`, `Month Name`, `Weekday`, `Weekday Name`, and `Hour` for enhanced analysis.
2. **Dashboard Design**: Created interactive visualizations to represent the key metrics.

## Conclusion

This project showcases my ability to analyze transaction data, identify key insights, and present them in a user-friendly dashboard. The strategic analysis provided through this project aims to empower stakeholders with actionable insights to drive business growth.
