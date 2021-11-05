[This is a project from Kaggle Competition: House Prices - Advanced Regression Techniques
Predict sales prices and practice feature engineering, RFs, and gradient boosting](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)


Download kaggle data set -- > kaggle competitions download -c house-prices-advanced-regression-techniques

:house_with_garden: A large data set with 79 different features (like living area, number of rooms, location, etc.) and their prices are provided for residential homes in Ames, Iowa. The challenge is to learn a relationship between the essential features and the price and predict the prices of a new set of houses.

:infinity:	 This model predicts the sales price for each house. For each Id in the test set, we must predict the value of the SalePrice variable. 

:heavy_check_mark: Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)
