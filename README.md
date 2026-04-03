# E-commerce Customer & Demand Analytics

## Overview
This project analyses the Brazilian E-Commerce Public Dataset by Olist to understand customer behaviour, category performance, and short-term demand patterns.

The project combines data preparation, KPI reporting, behavioural analysis, directional performance review, and weekly demand forecasting to generate practical business recommendations.

## Business Objective
The objective was to explore how e-commerce transaction data can support decisions related to:
- customer behaviour and repeat purchasing
- category performance and revenue concentration
- short-term demand planning

## Dataset
Source: Brazilian E-Commerce Public Dataset by Olist

Main tables used:
- orders
- order items
- payments
- products
- customers
- product category translation

## Project Workflow
1. Loaded and reviewed multiple source tables
2. Built clean order-level and item-level datasets
3. Analysed key commercial KPIs
4. Examined customer segments and top product categories
5. Conducted a directional pre/post performance comparison
6. Developed a weekly demand forecast using exponential smoothing
7. Generated business recommendations based on the findings

## Key Insights
- Revenue was concentrated in a relatively small number of product categories.
- Repeat purchasing represented a relatively small share of customer activity.
- Weekly demand showed both strong growth and noticeable short-term volatility.
- A seasonal forecasting model provided a useful planning baseline, but exception review remained important for high-volatility weeks.

## Business Recommendations
- Focus retention efforts more selectively on categories or segments with stronger repeat potential.
- Monitor category concentration to reduce over-reliance on a small number of revenue drivers.
- Use short-term forecasts as a planning baseline, supported by exception-based business review.

## Tools Used
- Python
- Pandas
- Matplotlib
- Statsmodels
- Scikit-learn
- Jupyter Notebook

## Repository Structure
```text
ecommerce-customer-demand-analytics/
├── notebooks/
├── outputs/
├── README.md
