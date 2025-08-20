# Avocado Prices and Sales Time Series Forecasting

This project analyzes and forecasts avocado prices and sales volume in multiple US markets using historical data. The dataset includes weekly retail scan data for Hass avocados, broken down by region, type (conventional vs. organic), and sales features.

## Repository Contents
- AvocadoSales.ipynb → Notebook with analysis, visualization, and forecasting models  
- avocado.csv → Dataset with historical avocado prices and sales  

## Dataset Information
Columns include:
- Date, AveragePrice, Total Volume  
- PLU codes (4046, 4225, 4770)  
- Bag sales (Small, Large, XLarge)  
- Type (conventional/organic), Year, Region  

## Project Workflow
1. Exploratory data analysis (trends, regions, types)  
2. Time series forecasting (ARIMA, Prophet)  
3. Visualization of trends and predictions  

## How to Run
1. Clone the repository  
2. Install required libraries (`pip install -r requirements.txt`)  
3. Open `AvocadoSales.ipynb` in Jupyter Notebook  

## Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Statsmodels (ARIMA)  
- Prophet  
- Jupyter Notebook  
  

## Author
Raghad Almaghraby  
GitHub: [raghad006](https://github.com/raghad006)

## License
MIT License
