# Power Consumption Forecasting (LSTM)

This project performs electric power consumption forecasting using:
- Data cleaning and preprocessing
- Resampling (daily, weekly, monthly, hourly)
- Statistical analysis and visualizations
- Supervised time-series preparation
- LSTM model for forecasting
- Evaluation using RMSE and visual comparison

The notebook includes exploratory analysis, feature resampling, scaling, model building and predictions.

## Dataset
The project uses the UCI Household Power Consumption dataset  
(loaded from Google Drive or locally as `household_power_consumption.txt`).

## Files
- Electric_Power.ipynb — main notebook  
- requirements.txt — dependencies  
- .gitignore — ignored files  
- assets/ — optional: loss curves, actual vs predicted plots

## Notes
LSTM uses hourly-resampled data with scaled features and supervised sequence formatting.
