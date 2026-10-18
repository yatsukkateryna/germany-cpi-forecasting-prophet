# germany-cpi-forecasting-prophet
Time-series machine learning project forecasting Germany's Consumer Price Index (CPI) using Python, FRED API, and Meta's Prophet algorithm

A machine learning project bridging Economics and Data Science. This project extracts historical macroeconomic data for Germany via the FRED API and uses Meta's Prophet algorithm to model non-linear trends, yearly seasonality, and forecast future Consumer Price Index (CPI) levels.

 Project Overview
- **Goal:** Build an automated pipeline to forecast Germany's inflation dynamics (CPI).
- **Data Source:** Federal Reserve Economic Data (FRED) API ('CP0000DEM086NEST' ticker).
- **Time Horizon:** Monthly historical CPI data.
- **Evaluation Metric:** Mean Absolute Percentage Error (MAPE) on a 12-month holdout test set.

Results & Key Takeaways
- **Model Performance:** The Prophet model achieved a MAPE of 2.10% on the 12-month forecast horizon.
- **Seasonality Insights:** The decomposition revealed clear intra-year price patterns alongside the overarching macroeconomic trend.
