🚖 Time Series Car Dataset – Sprint 13
Best Model to Predict Most Demanding Time for Sweet Lift Taxis

📌 Project Overview
This project aims to help Sweet Lift, a taxi service provider, predict peak demand periods using time series data. By identifying high-demand hours, the company can optimize driver allocation, reduce hiring costs, and improve customer satisfaction through better service availability.

🔍 Key Features
* Predicts peak demand hours for taxi rides.
* Implements and compares multiple regression models.
* Resamples data on an hourly basis for improved temporal analysis.
* Extracts time-based features: hour, day, weekday, and month.
* Handles missing values and prepares data for robust model training.

🧹 Data Preprocessing
* Resampled data at hourly intervals.
* Created temporal features: hour, day, day of the week, month.
* Dropped missing values from the training dataset.
* Split data into training and testing sets.

🤖 Model Comparison
Model	                RMSE (Test)
* DecisionTreeRegressor	21.34
* RandomForestRegressor	22.55
* LightGBMRegressor	    44.62
* XGBoostRegressor	    Similar to LightGBM
* LinearRegression	    Worst performance

🌟 Why LightGBMRegressor?
Despite a higher RMSE, LightGBMRegressor was selected due to:
* Efficient handling of non-linear relationships and high-dimensional data.
* Fast training time compared to other gradient boosting models.
* Clear feature importance ranking for interpretability.
* Reliable performance for demand forecasting.


BLANK_README.md to get started Build With: This is the list of the libraries used by me to run this project were pandas, numpy, matplotlib.pyplot, train_test_split, LGBMClassifier, seasonal_decompose, ColumnTransformer,StandardScaler,
LinearRegression, DecisionTreeRegressor, RandomForestRegressor, LGBMRegressor, XGBRegressor, TimeSeriesSplit, mean_squared_error 
Getting Started: This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple steps.
Prequisites: This is an example of software and how to install them. VS Code How to Run Clone this repository: https://github.com/sohini8328/Time_series_car_dataset_Sprint_13.git
Contributors- Sohini Tomar


