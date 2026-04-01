#**🍔 Food Delivery Time Prediction**

**Project Overview**

This project predicts the time required to deliver food orders based on factors like distance, weather, traffic, and time of day. It demonstrates a complete machine learning workflow from data cleaning to model evaluation.

**Dataset**

The dataset includes:

Distance between restaurant and customer

Weather conditions (Clear, Rainy, Foggy, Snowy, Windy)

Traffic density (Low, Medium, High)

Time of day

🎯 Target variable: Delivery time (in minutes)\

**Steps Performed**

Imported libraries for analysis and modeling
Loaded and inspected the dataset
Handled missing values and removed duplicates
Exploratory Data Analysis (EDA): univariate & bivariate analysis, correlation heatmap
Detected and handled outliers
Encoded categorical variables and applied log transformation
Separated features and target variable
Split the data into training and testing sets
Applied feature scaling
Trained multiple regression models: Linear Regression, KNN, Decision Tree, Random Forest, Gradient Boosting, XGBoost, SVR
Evaluated models using MAE, MSE, RMSE, MAPE, R² Score, Adjusted R²
Results
Compared all models based on evaluation metrics
Identified the best performing model for predicting delivery time

**Conclusion**

This project shows a complete machine learning workflow from data cleaning to regression modeling.
Future Improvements: Include real-time traffic data, consider restaurant preparation time, deploy as a web app 🌐
