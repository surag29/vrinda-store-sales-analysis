# vrinda-store-sales-analysis

## Project Overview

This is a comprehensive data analysis project on Vrinda Store's annual sales data for 2022. The analysis involves data cleaning, processing, and visualization of sales trends across multiple dimensions including customer demographics, sales channels, geographic distribution, and order status.

## Dataset

- **Dataset File**: `Vrinda Store Dataset.xlsx`
- **Time Period**: January 2022 - December 2022
- **Key Data Points**: Order information including customer details, sales amounts, order status, and channel information

## Analysis Steps & Methodology

### 1. Data Cleaning & Processing
- Removed duplicate records and handled missing values
- Standardized data formats across all columns
- Validated data consistency and integrity

### 2. Exploratory Data Analysis
- Analyzed sales patterns across months
- Identified top-performing states and regions
- Examined customer demographics by age and gender
- Assessed sales channel performance

### 3. Pivot Tables & Aggregation
- Created pivot tables for multi-dimensional analysis
- Aggregated sales by state, channel, and customer segments
- Calculated order metrics including status distribution

### 4. Visualization & Dashboard
- Built an interactive Excel dashboard with multiple visualizations
- Implemented filters for Month, Channel, and Category analysis

## Dashboard Visualizations

![Dashboard Screenshot](Screenshot%202026-01-05%20135637.png)

### Key Charts & Metrics:

**1. Orders vs Sales (Monthly Trend)**
- Dual-axis chart showing order count and sales amount by month
- Reveals seasonal patterns and sales performance correlation

**2. Sales: Men vs Women (Gender Distribution)**
- Pie chart indicating that women account for 64% of total sales
- Men account for 36% of sales
- Insight: Female customers are a major revenue driver

**3. Order Status Distribution**
- Delivered: 92% (Primary order fulfillment rate)
- Refunded: 2%
- Returned: 3%
- Cancelled: 3%
- Insight: High delivery success rate indicates operational efficiency

**4. Sales by Top 5 States**
- Tamil Nadu: 1.68M
- Telangana: 1.71M
- Uttar Pradesh: 2.10M
- Karnataka: 2.65M
- Maharashtra: 2.99M
- Insight: Southern and Western states drive majority of sales

**5. Orders by Age Group vs Gender**
- Adult age group: 34.59% of orders (primarily women at 21.13%)
- Senior age group: 13.70% of orders
- Teenager age group: 9.20% of orders
- Insight: Adult women form the largest customer segment

**6. Orders by Sales Channel**
- Myntra: 23% of orders
- Nalli: 4%
- Others: 4%
- Amazon: 35% (Largest sales channel)
- Flipkart: 22%
- Meesho: 2%
- Ajio: 6%
- Insight: Amazon and Flipkart are dominant channels, accounting for 57% of orders

## Key Findings & Business Insights

1. **Customer Demographics**: Women customers represent 64% of sales, making them the primary target audience

2. **Geographic Performance**: Top 5 states contribute significantly to revenue, with Maharashtra leading at 2.99M

3. **Channel Strategy**: Amazon (35%) and Flipkart (22%) are the most effective sales channels

4. **Order Fulfillment**: 92% delivery success rate demonstrates strong logistics and operational capability

5. **Age Group Analysis**: Adult segment (34.59%) shows the highest engagement, particularly among women

## Files in This Repository

- `README.md` - This file, providing project overview and analysis summary
- `INSIGHTS.md` - Detailed analysis insights and business recommendations
- `Vrinda Store Dataset.xlsx` - Raw dataset containing all transaction records
- `Vrinda Store Data Analysis.xlsx` - Processed data with pivot tables and analysis
- `Screenshot 2026-01-05 135637.png` - Dashboard screenshot showing all visualizations

## Tools & Technologies Used

- **Microsoft Excel** - Data cleaning, pivot tables, and dashboard creation
- **Data Visualization** - Charts, graphs, and interactive filters

## How to Use This Repository

1. Review the `Vrinda Store Dataset.xlsx` to understand the raw data structure
2. Check the `Vrinda Store Data Analysis.xlsx` to see the processed data and pivot tables
3. View the dashboard screenshot for visual analysis
4. Read `INSIGHTS.md` for detailed findings and business recommendations

## Future Enhancements

- Time-series forecasting for sales prediction
- Customer segmentation analysis using RFM methodology
- Profitability analysis by channel and customer segment
- Seasonal decomposition for better trend understanding
