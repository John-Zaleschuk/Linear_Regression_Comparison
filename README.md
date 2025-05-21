# Linear Regression Comparison on Housing Data

## Intro
The goal of this project was to use several linear regression models to predict housing costs using publicly avaible housing data. This dataset is featured on [kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) as a competition on advanced linear regression techniques. The data is a collection of 81 features from residential homes in Ames, Iowa. 

<br>

## Feature Impact

The largest improvement of the model came from extensive preprocessing of the data, combining features, convering categorical values, and using logarithmic functions to standardize the variation in home price. The feature with the highest impact on the model was square footage, seen from the correlation function below.

<p align="left">
  <img src="https://github.com/John-Zaleschuk/Linear_Regression_Comparison/blob/main/images/sqft_v_price.png" width="400"/>
</p>

<br>

## Regression Comparison

All of the linear regression models underwent some fine tuning of parameters to increase accuracy, with the result ending in fairly consistent performance across the board.

<p align="left">
  <img src="https://github.com/John-Zaleschuk/Linear_Regression_Comparison/blob/main/images/comparison_graph.png" width="1000"/>
</p>

<br>

## Accuracy and RMSE
Lasso regression slightly underperformed the other models, with around 5-10% less overall accuracy. Ridge regression slightly outperformed Linear regression across all five folds.

<p align="left">
  <img src="https://github.com/John-Zaleschuk/Linear_Regression_Comparison/blob/main/images/prog_output.png" width="400"/>
</p>
