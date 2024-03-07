Objective
The objective of this data analytics project is to develop and validate a predictive model for Tip Amount in New York City taxis and limousines. The dataset used, collected by the NYC Taxi and Limousine Commission (TLC), covers yellow taxi trip data from February 2016.

Data Background
Over thirteen thousand registered taxis in NYC.
Dataset attributes include pick-up/drop-off dates, locations, distances, fares, rate types, payment types, and passenger counts.
Yellow taxis respond to street hails in all five boroughs.
Data Analysis Process
1. Data Exploration and Pre-processing
Checked for missing values: None found.
Feature engineering for better insights, including trip duration, day of the week, hour of the day, geolocation, and tip fraction.
Data cleaning for consistency and accuracy.
2. Data Visualization
Visualized taxi pickups and drop-offs on a map.
Explored the correlation between tip amounts, weekdays, hours, and rate codes.
3. Correlation Analysis
Examined correlations between different features using Pearson correlation.
Selected relevant variables for model building based on correlation.
4. Model Building
Built and evaluated four regression models:

Linear Regression
Decision Tree Regression
Random Forest Regression
Gradient Boosting Regression
5. Model Evaluation
Evaluated models using Root Mean Squared Error (RMSE) as the performance metric.

Results and Conclusions
Best-performing model: Gradient Boosting Regressor with an RMSE of 1.0174.
Applied GridSearchCV to optimize hyperparameters.
Model accuracy: 86.7%.
Best Model RMSE Comparison
Linear Regression: 1.320
Decision Tree Regression: 1.274
Random Forest Regression: 1.095
Gradient Boosting Regressor: 1.0174
This project provides insights into tipping behavior in NYC taxis and establishes a reliable predictive model for future tip amount estimations.
