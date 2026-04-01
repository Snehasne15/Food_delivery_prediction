#🍔 Food Delivery Time Prediction
##📖 Project Overview

This project predicts the time required to deliver food orders based on factors like distance, weather, traffic, and time of day. It demonstrates a complete machine learning workflow, from data cleaning to model evaluation.

##🗂️ Dataset

The dataset includes:

🛣️ Distance between restaurant and customer
🌦️ Weather conditions (Clear, Rainy, Foggy, Snowy, Windy)
🚦 Traffic density (Low, Medium, High)
🕒 Time of day
🎯 Target variable: Delivery time (in minutes)
🛠️ Steps Performed
📥 Imported required libraries for analysis and modeling
📂 Loaded and inspected the dataset
🧹 Handled missing values and removed duplicates
🔍 Performed Exploratory Data Analysis (EDA):
📊 Univariate analysis (histograms, bar plots)
🔗 Bivariate analysis (scatter plots, box plots)
🧩 Correlation heatmap
⚠️ Detected and handled outliers
🔢 Encoded categorical variables and applied log transformation
🧮 Separated features and target variable
✂️ Split the data into training and testing sets
📏 Applied feature scaling
🤖 Trained multiple regression models:
Linear Regression
KNN Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor
Support Vector Regressor (SVR)
Used k-fold and stratified k-fold cross-validation
📈 Evaluated models using: MAE, MSE, RMSE, MAPE, R² Score, Adjusted R²
📊 Results
Compared all models based on evaluation metrics
Identified the best performing model for predicting delivery time
✅ Conclusion

This project demonstrates the full machine learning workflow from data cleaning to regression modeling. It helps understand the factors affecting delivery time and builds a model for accurate prediction.
