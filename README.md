# house_prices
In this repo I perform an indepth analysis into the House prices kaggle competition - https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques.

In eda.ipynb I do a through Exploratory Data Analysis: dealing with missing values, encoding catagorical data, mutual information, correlation heatmap, feature engineering, scaling.

I use my eda to build models in the remaining files. In model.ipynbn I build a linear regression model, as well as regularised linear regression (Lasso, Rigde Elastic). I then build a random forest model and XGBoost model. I tune hyperparameters then stack various models togther to improve performance.