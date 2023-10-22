# Global_AI_Hub_Melbourne_Housing_Price_Predictions_ML_Project

Hello everybody,

In this Machine Learning Project for 'Housing Price Predictions with Melbourne
Housing Dataset' I identified and removed all NaN values in the categorical and numeric ('float64') columns by replacing them with their respective modes. Then I've made some visualization tasks to show the relations between the pricing and the categorical variables of the dataset. To make a price estimation I have used the label encoding method on the categorical columns instead of one-hot encoding to prevent high memory usage because the nunique size is to big. For model selection I used Lasso, LinearRegression, Ridge, ElasticNet, KNeighborsRegressor, RandomForestRegressor, GradientBoostingRegresor and the AdaBoostRegressor. And finally to make the model evaluation I calculated the Mean Absolute Error (MAE), the Mean Squred Error (MSE), the Root Mean Squared Error (RMSE) using Numpy .sqrt() function by using 'mse' as parameter and the R-squared value (R2).

I hope this project is useful for your works and gives you some tips and tricks for your future projects. Enjoy it!

Thank you!
