# Linear Regression for House Price Prediction

This project involves building a linear regression model to predict house prices based on several features such as transaction date, house age, distance to the nearest MRT station, number of convenience stores, latitude, and longitude.

## Dataset

The dataset used for this project is stored in a CSV file named `Real estate.csv`. The dataset contains the following columns:

- **No**: Index of the data point
- **X1 transaction date**: Transaction date
- **X2 house age**: Age of the house
- **X3 distance to the nearest MRT station**: Distance to the nearest Mass Rapid Transit (MRT) station
- **X4 number of convenience stores**: Number of convenience stores nearby
- **X5 latitude**: Latitude of the location
- **X6 longitude**: Longitude of the location
- **Y house price of unit area**: House price per unit area (target variable)

## Approach

1. **Data Preparation**: The dataset is loaded into a Pandas DataFrame. The features (X) and target variable (y) are separated.

2. **Model Training**: A linear regression model is created and trained using the training data.

3. **Model Evaluation**: The trained model is used to make predictions on the testing set. Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE) are calculated to evaluate the performance of the model.

## Results

The performance metrics for the linear regression model are as follows:

- Mean Squared Error (MSE): 53.50561912450505
- Mean Absolute Error (MAE): 5.305355690074272
- Root Mean Squared Error (RMSE): 7.314753524521866lue]

## Conclusion

Based on the evaluation metrics, the linear regression model performs reasonably well in predicting house prices. Further optimization and feature engineering could potentially improve the model's performance.

