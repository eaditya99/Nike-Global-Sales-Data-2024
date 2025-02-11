# Nike Global Sales Data Analysis

## Project Overview
This project aims to analyze Nike's global sales data for 2024, providing insights into regional sales performance, product demand, and key market trends. By leveraging machine learning models and data visualization techniques, we identify patterns that can drive strategic decision-making for inventory management, pricing, and marketing strategies.

## Context
Nike, as a global leader in sportswear and footwear, operates across multiple regions with diverse consumer preferences. Understanding sales trends in different regions helps the company optimize product distribution, pricing strategies, and marketing efforts. By analyzing this dataset, we gain valuable insights into which regions and product lines contribute most to revenue, seasonal fluctuations, and the impact of online sales.

## Problem Statement
The objective of this analysis is to:
- Identify the top and bottom-performing regions in terms of revenue.
- Determine the best and worst-selling products in each region.
- Analyze seasonal sales trends and their impact on revenue.
- Evaluate the contribution of online sales to overall revenue.
- Conduct pricing analysis to assess its effect on product performance.

## Stakeholders
- **Nike Sales & Marketing Teams**: Utilize insights to optimize marketing campaigns and sales strategies.
- **Supply Chain & Inventory Managers**: Improve demand forecasting and inventory allocation.
- **Business Executives & Decision-Makers**: Drive strategic planning based on data-driven insights.
- **E-commerce & Retail Teams**: Enhance online and offline sales strategies based on product performance.

## Goals
- **Identify Regional Sales Trends**: Highlight the top and bottom-performing regions.
- **Analyze Product Demand**: Determine which products contribute most to revenue in different regions.
- **Understand Seasonal Variations**: Detect seasonal sales fluctuations to optimize inventory planning.
- **Evaluate Online Sales Impact**: Assess the contribution of online sales to overall revenue.
- **Conduct Pricing Analysis**: Provide recommendations based on price sensitivity and consumer purchasing behavior.

## About the Dataset
Explore a comprehensive dataset of Nike's global sales for the year 2024, spanning multiple regions, product categories, and price tiers.

### Key Features:
- **Regions**: Greater China, Japan, South Korea, India, Southeast Asia, America, Europe.
- **Categories**: Footwear, Apparel, and Equipment, with various sub-categories and product lines.
- **Metrics**: Units sold, revenue (USD), retail prices, and online sales percentages.
- **Dataset Source**: [Nike Global Sales Data 2024 on Kaggle](https://www.kaggle.com/datasets/ayushcx/nike-global-sales-data-2024)

## Business Questions
1. **Top 5 Regions & Bottom 5 Regions**
2. **Product Performance in Top 5 Regions**: Identify the best and worst-performing products in each top region.
3. **Product Performance in Bottom 5 Regions**: Identify the best and worst-performing products in each bottom region.
4. **Seasonality Analysis**: Examine seasonal product trends in top-performing regions.
5. **Annual Category Sales**: Total units sold for each product category over the year.
6. **Sub-Category Breakdown**: Detailed breakdown of sales for each sub-category.
7. **Online Sales Contribution**: Measure online sales impact on overall revenue and category performance.

## Machine Learning Model
### Models Used:
- **Linear Regression**
- **XGBoost Regressor**

### Evaluation Metrics:
1. **Mean Absolute Error (MAE)**
2. **Root Mean Squared Error (RMSE)**
3. **R-squared (R²)**

The XGBoost model was selected based on its superior performance in predicting sales trends.

## Dashboard Insights
- **Top & Bottom Performing Regions**
- **Product Contribution Analysis**
- **Seasonal Demand Patterns**
- **Pricing & Online Sales Impact**

View the interactive dashboard here: [Nike Global Sales Dashboard](https://public.tableau.com/app/profile/edo.aditya6263/viz/NikeGlobalSalesData/NikeSales2024)

## Recommendations
1. **Optimize Inventory for Top Regions**: Adjust stock levels based on peak seasons and best-performing products.
2. **Boost Sales in Bottom Regions**: Target low-performing regions with localized marketing and promotional campaigns.
3. **Enhance Online Sales Strategy**: Leverage e-commerce growth by optimizing online-exclusive offers.
4. **Price Sensitivity Analysis**: Adjust pricing strategies based on regional and product-specific trends.

## Future Work

- **Real-Time Price Optimization**: Implement dynamic pricing adjustments based on real-time demand and competitor pricing trends.
- **Advanced Sales Forecasting**: Improve demand prediction using time-series modeling and external economic indicators.
- **Advanced Feature Engineering**: Integrate additional external data sources (e.g., macroeconomic indicators, competitor pricing).  
- **Deep Dive into Consumer Behavior**: Leverage customer insights to refine marketing strategies.
- **Advanced Feature Engineering**: Integrate additional external data sources (e.g., macroeconomic indicators, competitor pricing).
- **Deep Dive into Consumer Behavior**: Leverage customer insights to refine marketing strategies.

This document serves as a roadmap for leveraging data-driven insights to optimize Nike’s global sales strategy.
