# Flights Price Prediction

## Overview
This is a project made to  estimate the cost of airline tickets using machine learning based on various features like departure date, airline, duration, number of stops, and more. Accurate predictions can help users make informed decisions when booking flights and assist travel platforms in offering personalized pricing suggestions.

## Tools Used
- Pandas and NumPy for data manipulation
- RandomForestRegressor as the main machine learning model
- Matplotlib & Seaborn for data visualization
- Scikit-learn for machine learning models and preprocessing tools
- Google Colab as the development environment

## Dataset 
The [dataset](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction) was obtained from kaggle. Dataset contains information about flight booking options from the website Easemytrip for flight travel between India's top 6 metro cities. There are 300261 datapoints and 11 features in the cleaned dataset.

## Results
![](https://github.com/IssabelAverina/PersonalProjects/blob/0c360051d16f0cb7e3b17416d57c6e7ad46d6ad4/FlightsPricePrediction/flight.png)
| Metric                             | Before Tuning | After Tuning | Explanation                                                                                           |
| ---------------------------------- | ------------- | ------------ | ----------------------------------------------------------------------------------------------------- |
| **R² Score**                       | 0.9856        | 0.9865       | The model was able to explain **98.65%** of the variation in flight prices.                           |
| **MAE (Mean Absolute Error)**      | 1065.08       | 1080.68      | On average, predictions are off by **1080**, which is quite low given the typical flight price range. |
| **RMSE (Root Mean Squared Error)** | 2730.96       | 2641.95      | Most predictions are quite close, with few large errors.                                              |

The graph shows that the predictions are very close to the actual price with few outliers.
The model is highly accurate, especially considering flight prices can vary from a few thousand to over ₹100,000. An MAE of ~₹1,000 is strong.

![](https://github.com/IssabelAverina/PersonalProjects/blob/e453f5f07a99d3196ba4cf9619a249140667709d/FlightsPricePrediction/features.png)
From the plotted graph above, we can also see that the most important feature affecting the airline price is the class (Economy/Business), duration and days_left followed but has significantly lower impact.

## Future Improvements
- Using GridSearchCV to find the best model configuration that will be more accurate.
- Try other models like XGBoost or deep learning.
