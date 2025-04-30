# Time_series_car_dataset_Sprint_13
Time_series_car_dataset_Sprint_13


Best Model to Predict Most Demanding Time for Sweet Lift Taxis
Introduction
The goal of this project is to assist Sweet Lift in developing a machine learning model to predict peak demand periods for taxi rides. By identifying the busiest times of the day, the company can efficiently hire more drivers when needed and allocate resources effectively. Additionally, by focusing on optimized marketing channels, Sweet Lift can reduce hiring costs while ensuring better service availability for customers.
Features
- Predicts peak demand hours for taxi rides
- Implements multiple regression models for comparison
- Resamples data on an hourly basis for better analysis
- Extracts key temporal features such as hour, day, day of the week, and month
- Handles missing values and prepares data for efficient model training
- 
Data Preprocessing
- Resampling data by hourly intervals
- Creating features such as hour, day, day of the week, and month
- Dropping missing values from the training dataset
- Splitting data into training and testing sets

Model Comparison
Several models were trained and compared to identify the best-performing one:
| Model | RMSE (Test) | 
| DecisionTreeRegressor | 21.34 | 
| RandomForestRegressor | 22.55 | 
| LightGBMRegressor | 44.62 | 
| XGBoostRegressor | Similar to LightGBM | 
| LinearRegression | Worst performance | 

Why LightGBMRegressor?
The LightGBMRegressor was identified as the optimal model due to:
- Handling non-linear relationships and high-dimensional datasets effectively
- Fast training time compared to complex gradient boosting models
- Providing a clear ranking of feature importance for better interpretability
- Lower RMSE score, ensuring accurate demand prediction
Conclusion
Using this project, Sweet Lift will successfully implement a machine learning model to predict peak demand periods, ensuring efficient driver allocation and improved customer satisfaction. With LightGBMRegressor, the company can reliably estimate high-demand hours and plan hiring accordingly, minimizing unnecessary costs while maximizing availability.

BLANK_README.md to get started Build With: This is the list of the libraries used by me to run this project were pandas, numpy, matplotlib.pyplot, train_test_split, LGBMClassifier, seasonal_decompose, ColumnTransformer,StandardScaler,
LinearRegression, DecisionTreeRegressor, RandomForestRegressor, LGBMRegressor, XGBRegressor, TimeSeriesSplit, mean_squared_error 
Getting Started: This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple steps.
Prequisites: This is an example of software and how to install them. VS Code How to Run Clone this repository: https://github.com/sohini8328/Time_series_car_dataset_Sprint_13.git
Contributors- Sohini Tomar


