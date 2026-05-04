# 📈 Stock Price Prediction Dashboard

## Project Overview
Built an end-to-end stock price prediction pipeline using 
Python Machine Learning and Tableau visualization.

## Tools Used
- Python (yfinance, scikit-learn, pandas, numpy)
- Tableau Desktop
- Linear Regression ML Model

## Model Performance
- R² Accuracy : 88.4%
- MAPE        : 1.22% (avg error)
- MAE         : ₹31.17

## Project Steps
1. Downloaded RELIANCE.NS stock data using yfinance
2. Created 14 features (Moving Averages, Lag prices, Volatility)
3. Trained Linear Regression model on 80% of data
4. Tested on remaining 20% — achieved 88% accuracy
5. Exported predictions to CSV
6. Built interactive Tableau dashboard

## Dashboard Features
- Actual vs Predicted price line chart
- Buy vs Hold signal bar chart
- Date range: June 2024 - December 2024

## Files
| File | Description |
|------|-------------|
| stock_predictor.py | Main Python ML code |
| stock_predictions.csv | Model output with signals |
| stock_history.csv | Full price history with indicators |

## How to Run
pip install yfinance scikit-learn pandas numpy
python stock_predictor.py
