# Iowa-Liquor-Sales-Analysis-Forecasting
This project analyzes Iowa’s liquor sales data to uncover trends, identify top-selling products, and generate insights that can guide business decisions. The dataset comes from the Iowa Department of Commerce and was combined with SQL querying and Power BI visualization for actionable insights.

## Basic Information

**Person or organization developing model:** Robert Bhero, robert.bhero@gwu.edu  
**Model date:** July 2025  
**Model version:** 1.0  
**License:** MIT  
**Model implementation:**

---

## Intended Use

**Primary intended uses:**  
This project is intended for educational and analytical purposes, demonstrating how to use SQL, Python, and Power BI for large-scale retail sales analysis. It explores sales patterns by location, product category, and seasonality, and builds demand forecasts to support inventory and staffing decisions.  

**Primary intended users:**  
Data analysts, business owners, supply chain planners, and students learning data analytics.  

**Out of scope use cases:**  
Any direct commercial use without further validation or use for financial decision-making without considering additional market data.

---

## Training Data

**Data source:** Iowa Department of Commerce – Public Liquor Sales Dataset  

**Data dictionary:**  

| Column Name           | Description |
|-----------------------|-------------|
| Invoice/Item Number   | Unique identifier for the transaction line |
| Date                  | Date of sale |
| Store Number          | Store ID |
| Store Name            | Name of the store |
| City                  | City where the store is located |
| Zip Code              | Postal code |
| County                | County name |
| Category              | Liquor product category |
| Category Name         | Description of product category |
| Vendor Number         | Vendor ID |
| Vendor Name           | Vendor company name |
| Item Number           | Product code |
| Item Description      | Product name |
| Bottle Volume (ml)    | Volume of product in milliliters |
| State Bottle Cost     | Purchase cost per bottle to the state |
| State Bottle Retail   | Selling price per bottle |
| Bottles Sold          | Number of bottles sold |
| Sale (Dollars)        | Total sales in USD |
| Volume Sold (Liters)  | Volume sold in liters |
| Volume Sold (Gallons) | Volume sold in gallons |

**Number of rows:** ~25 million (raw dataset before filtering).  

**Data preparation:** Cleaned missing values, standardized product categories, converted dates to time series format, and created aggregated tables in SQL for analysis in Power BI.

---

## Model / Analysis Overview

**Approach:**  
- SQL queries to extract and aggregate key metrics (total sales, top stores, top products, seasonal trends).  
- Python for time series forecasting (Prophet and ARIMA models).  
- Power BI dashboard for interactive exploration.  

**Forecasting goal:** Predict demand for top-selling products and peak sales periods to optimize inventory and staffing.  

---

## Quantitative Analysis

**Key insights:**  
- Seasonal spikes in sales during holidays (December highest, July second).  
- Top-selling products are concentrated in a few categories, especially whiskey and vodka.  
- Certain counties consistently outperform others in sales per capita.  
- Forecast models predict continued growth in premium liquor categories.  

**Validation metrics:**  
- Time series forecast accuracy measured with MAE and RMSE.  
- Backtesting with historical sales data to evaluate forecast reliability.

---

## Ethical Considerations

While liquor sales forecasting can benefit businesses, it also raises public health concerns, such as promoting higher alcohol consumption. Insights from such models should be applied responsibly, balancing economic gains with social impact.  

---

## Limitations

- Dataset only includes state-managed liquor sales (excludes private beer/wine sales).  
- Forecasting models do not account for external factors like economic downturns or regulation changes.  
- Product categories are broad and may mask micro-level trends.

---

## What I Learned

- Writing optimized SQL queries for large datasets  
- Integrating Python forecasting models with Power BI dashboards  
- Handling time series data cleaning and preprocessing  
- Creating actionable business insights from sales data  
- Communicating data findings effectively  

---

## Future Improvements

- Incorporate demographic and economic data for richer context  
- Add more granular product segmentation  
- Experiment with deep learning forecasting methods (e.g., LSTM)  
- Deploy dashboard with live data connection for real-time monitoring  

---

## Final Notes

This project highlights how public sales datasets can be leveraged for meaningful business insights through the combination of SQL, Python, and Power BI. It provided valuable experience in large-scale data handling, forecasting, and dashboard reporting.










