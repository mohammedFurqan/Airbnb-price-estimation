# AirBnb listings price estimation

This project is an attempt to accurately estimate the prices of AirBnb listings. 

#### Data Source (Open Source)
http://insideairbnb.com/get-the-data.html

#### Models
- Regularised Linear Regression - Lasso, Ridge
- Ensemble methods - Random Forest, Gradient Boosting
- Neural Networks
- Support Vector Regression with RBF kernel

#### Feature selection steps:
- Removing features based on a certain threshold for missing values
- Imputing missing values appropriately
- P-values based feature selection
- LASSO feature selection
- Target-feature correlation based selection
- Retaining one of the features for every highly correlated pair(s) of features
