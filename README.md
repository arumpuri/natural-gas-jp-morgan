# Natural Gas Price Analysis

## Project Overview
This project provides a comprehensive analysis and predictive modeling tool for natural gas prices, utilizing Python data science libraries to extract insights from monthly price data.

---

## Features

### Data Loading and Preprocessing
- Converts raw CSV data into structured pandas DataFrame
- Adds time-based features (Year, Month, Season)

### Exploratory Data Analysis
- Calculates basic statistical measures
- Computes monthly and seasonal price averages
- Performs year-over-year trend analysis

### Visualization
- Time series price plot
- Monthly and seasonal price distributions
- Year-over-year price comparisons

### Predictive Modeling
- ARIMA and SARIMA-based price prediction
- Seasonal and trend component integration
- Future price forecasting

---

## Prerequisites

### Dependencies
- **Python 3.8+**
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `statsmodels`

---

## Project Structure

- **Nat_Gas.csv**: Raw price data file
- **gas_price_analysis.py**: Main analysis script
  - Data loading
  - Exploratory analysis
  - Visualization
  - Prediction model

---

## Key Analysis Components

### Data Preparation
- Convert dates to datetime
- Extract time-based features
- Prepare data for analysis

### Predictive Model
- ARIMA and SARIMA-based predictions
- Seasonal adjustments
- Trend component tracking

### Visualizations
- Time series plot
- Monthly price distribution
- Seasonal price variations
- Year-over-year comparisons

---

## Limitations

- Predictions based on historical patterns
- Limited by available historical data
- Does not account for unexpected market disruptions
