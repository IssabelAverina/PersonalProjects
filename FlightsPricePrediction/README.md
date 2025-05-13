# Flights Price Prediction

## Overview
This is a project made to  estimate the cost of airline tickets using machine learning based on various features like departure date, airline, duration, number of stops, and more. Accurate predictions can help users make informed decisions when booking flights and assist travel platforms in offering personalized pricing suggestions.

## Tools Used
- Pandas and NumPy for data manipulation
- RandomForestRegressor as the main machine learning model
- Matplotlib & Seaborn for data visualization
- Scikit-learn for machine learning models and preprocessing tools

## Dataset 
The [dataset](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction) was obtained from kaggle. Dataset contains information about flight booking options from the website Easemytrip for flight travel between India's top 6 metro cities. There are 300261 datapoints and 11 features in the cleaned dataset.

## Results
![](FlightsPricePrediction/flight.png)
| Metric                             | Before Tuning | After Tuning | Explanation                                                                                           |
| ---------------------------------- | ------------- | ------------ | ----------------------------------------------------------------------------------------------------- |
| **R² Score**                       | 0.9856        | 0.9865       | The model was able to explain **98.65%** of the variation in flight prices.                           |
| **MAE (Mean Absolute Error)**      | 1065.08       | 1080.68      | On average, predictions are off by **1080**, which is quite low given the typical flight price range. |
| **RMSE (Root Mean Squared Error)** | 2730.96       | 2641.95      | Most predictions are quite close, with few large errors.                                              |

The model is highly accurate, especially considering flight prices can vary from a few thousand to over ₹100,000. An MAE of ~₹1,000 is strong.

## Future Improvements
- Using GridSearchCV to find the best model configuration that will be more accurate.
- Try other models like XGBoost or deep learning.
