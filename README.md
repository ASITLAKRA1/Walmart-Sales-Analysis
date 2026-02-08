# Walmart-Sales-Analysis
End-to-end analysis of Walmart’s weekly sales data to uncover trends, seasonality, and key demand drivers, along with 12-week sales forecasting to support inventory planning.


# Walmart Sales Time Series Analysis

## Project Overview
A large retail chain with multiple outlets faces challenges in managing inventory due to fluctuating customer demand.  
This project analyzes historical weekly sales data from Walmart stores to uncover demand patterns, understand the impact of external factors, and forecast future sales to support better inventory planning.


## Dataset Description
The dataset contains 6,435 weekly sales records across multiple Walmart stores with the following features:

- Store – Store identifier  
- Date – Week of sales  
- Weekly_Sales – Sales for the given store in that week  
- Holiday_Flag – Indicates whether the week includes a holiday  
- Temperature – Average weekly temperature  
- Fuel_Price – Regional fuel cost  
- CPI – Consumer Price Index  
- Unemployment – Unemployment rate  


## Objectives
- Analyze weekly sales trends and seasonal patterns  
- Study the impact of economic and environmental factors on sales  
- Compare performance across stores  
- Forecast weekly sales for the next 12 weeks using time-series modeling  



## Approach
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Time-series decomposition (trend, seasonality, residuals)  
- SARIMAX modeling for forecasting  
- Model evaluation using RMSE  


## Key Insights
- Weekly sales exhibit strong annual seasonality  
- Holiday periods show noticeable sales spikes  
- Sales performance varies significantly across stores  
- Time-series forecasting provides actionable insights for inventory planning  


## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Statsmodels (SARIMAX)  


## Future Scope
- Include exogenous variables explicitly in forecasting models  
- Automate store-wise forecasting  
- Deploy forecasts using dashboards  



