# californiaHousePricePrediction

# California House Price Prediction Analysis

This repository contains a Python script that performs an analysis of the California House Price dataset using XGBoost Regressor for prediction. The script demonstrates various steps involved in the analysis, including data preprocessing, model training, and evaluation.

## Dependencies
The following dependencies are required to run the script:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost

You can install these dependencies using the following command:
```
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

## Dataset
The analysis utilizes the California House Price dataset. This dataset contains information about median income, house age, average number of rooms and bedrooms, population, average occupancy, latitude, longitude, and the median house value for different districts in California. The dataset was obtained from the StatLib repository and derived from the 1990 U.S. census.

The dataset is loaded using the `fetch_california_housing` function from scikit-learn. It consists of 20,640 instances with 8 numeric predictive attributes and the target variable, which is the median house value in hundreds of thousands of dollars.

## Analysis Steps
1. Importing the necessary dependencies and libraries.
2. Loading the California House Price dataset using `fetch_california_housing` function.
3. Creating a pandas DataFrame to store the dataset.
4. Exploring and visualizing the data by displaying the first 5 rows, statistical measures, and correlation heatmap.
5. Splitting the data into features (X) and target variable (y).
6. Splitting the data into training and test sets using `train_test_split`.
7. Training an XGBoost Regressor model on the training data.
8. Evaluating the model's performance on both the training and test data by calculating the R-squared error and mean absolute error.
9. Visualizing the actual prices vs predicted prices for the training data.
10. Making predictions on the test data and evaluating the model's performance.

The analysis provides insights into the correlation between features and the ability of the XGBoost Regressor model to predict house prices in California.

