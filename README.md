# Bike-Rental-Demand-Prediction
A bike rental service in Seoul city is facing issues with keeping up with the rental demands of bikes in the city.To ensure seamless bike rental service in the city, a machine learning model has been developed to proactively estimate and anticipate the future demand for bikes. This predictive system aims to prevent service disruptions and cater to the increasing needs of bike rentals effectively.

# About the dataset

• Date : year-month-day

• Rented Bike count - Count of bikes rented at each hour

• Hour - Hour of the day

• Temperature-Temperature in Celsius

• Humidity - %

• Windspeed - m/s

• Visibility - 10m

• Dew point temperature - Celsius

• Solar radiation - MJ/m2

• Rainfall - mm

• Snowfall - cm

• Seasons - Winter, Spring, Summer, Autumn

• Holiday - Holiday/No holiday

• Functional Day - NoFunc (Non Functional Hours), Fun(Functional hours)


# Approach to solve the problem:

Data cleaning

Performing EDA

Encoding of categorical columns

Feature scaling

Fitting different models (Linear Regression, Decision Tree Regressor, Gradient Boost)

Evaluation of models using R-squared, RMSE, RSE, MAE metrics.


# Conclusion:

An R-squared value of 0.88 was acheived using Gradient Boost Regressor.
