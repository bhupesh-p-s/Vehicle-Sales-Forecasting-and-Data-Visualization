# Vehicle Sales Forecasting and Data Visualization

This project focuses on forecasting vehicle sales using time series modeling and visualizing sales trends over a 7-year period. The dataset contains domestic vehicle sales data across various categories such as Passenger Cars (PV), Utility Vehicles (PV), and Vans (PV).

## Project Overview

- **Goal**: Predict future vehicle sales and uncover insights from past trends using statistical models and visualizations.
- **Key Techniques**: 
  - Time series forecasting using ARIMA model.
  - Exploratory Data Analysis (EDA) for trend discovery.
  - Data visualization to highlight patterns and seasonality.
  
## Features

- **Sales Forecasting**: Implemented an ARIMA model to predict sales for the next 6 months for each vehicle category.
- **Visualizations**: Created comprehensive plots to visualize year-wise and month-wise sales trends, category-level sales, and heatmaps for sales data.
- **Trend Analysis**: Insights into declining sales post-2017, seasonal peaks in the last quarter, and dominance of the Passenger Cars category.

## Data

The dataset consists of domestic vehicle sales from 2012 to 2019. Key columns include:
- `YrMth`: The date (year and month) of the record.
- `Category Name`: Vehicle category (e.g., Passenger Cars, Utility Vehicles).
- `Domestic Sale`: The number of units sold domestically.

## Methodology

1. **Exploratory Data Analysis (EDA)**: Analyzed the data to identify missing values, outliers, and trends.
2. **Time Series Modeling**: Applied ARIMA for time series forecasting at the vehicle category level.
3. **Visualization**: Used Matplotlib and Seaborn for visualizing:
   - Yearly and monthly sales trends.
   - Category-wise sales over time.
   - Heatmaps showing sales volume distribution across months and years.

## Key Insights

- **Decline in Sales Post-2017**: Domestic vehicle sales peaked in 2017 and declined sharply in 2018 and 2019.
- **Seasonality**: Strong sales spikes were observed in October and November, likely due to festive seasons or promotions.
- **Category Trends**: Passenger Cars dominated the market but experienced a decline after 2017, while Utility Vehicles remained stable.
