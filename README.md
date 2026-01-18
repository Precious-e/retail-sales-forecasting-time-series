# Retail Sales Analysis & Time Series Forecasting

## Project Description
This project analyzes five years of retail sales data to uncover trends,
seasonality, and product performance. The analysis includes data cleaning,
exploratory data analysis, feature engineering, and time-series forecasting
to support data-driven business decisions.

## Dataset
- 8,456 rows and 8 columns of historical retail sales data
- Columns include: date, store, product, category, units_sold, unit_price,
  discount_applied, and payment_method
- Data contains missing values and inconsistencies to simulate real-world data challenges

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels (Holt-Winters Exponential Smoothing)
- Scikit-learn

## Analysis Workflow
1. Data loading and inspection
2. Handling missing values and inconsistent text labels
3. Feature engineering (`total_sales`)
4. Aggregation of daily sales into monthly trends
5. Exploratory trend and seasonality analysis
6. Time-series forecasting using Naïve and Holt-Winters models
7. Model evaluation using MAE and MAPE

## Key Insights
- Retail sales show strong seasonal patterns with recurring peaks each year
- Grocery and household products contribute the highest revenue
- Cleaning inconsistent product and category names significantly improves analysis accuracy
- Holt-Winters forecasting captures trend and seasonality better than a naïve baseline

## Business Recommendations
- Increase inventory before seasonal peak periods
- Use targeted discounts during low-sales months
- Leverage forecasts for inventory planning and staffing decisions

## How to Run
1. Clone the repository
2. Open the Jupyter Notebook
3. Run all cells in order to reproduce the analysis

## Author
Precious Eric  
GitHub: https://github.com/Precious-e
