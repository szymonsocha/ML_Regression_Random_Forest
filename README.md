## Description

In this project I am doing regression on weather data and making predictions on traffic. At the very beginning I do the data preparation. I clean them of outliers and prepare them for further prediction. To make predictions I use machine learning algorithms (Linear, Lasso, Ridge and Elastic Net Regression, Random Forest, KNN regressor, SVM), compare their performance and make predictions on a test set. The main task of the project is to make a prediction with the lowest possible prediction error as measured by MAPE (Mean Absolute Percentage Error).

Algorithms considered:

* Linear Regression, Lasso, Ridge, Elastic Net
* **Random Forest Regressor**
* k-Nearest Neighbors Regressor
* Support-Vector Machine

Algorithm selection:

* Manual Cross Validation parameter tuning
* Out-of-sample accuracy comparision of various algorithms
* **Random Forest Regressor with `n_estimators=1000`, `max_features=38`, `min_samples_split=19`, `max_depth=35`, `min_samples_leaf = 3`**

</br>
<p align="center">
  <img src="https://github.com/szymonsocha/ML_Regression_Random_Forrest/blob/main/data/rf_oos_predictions.jpg?raw=true" alt="Random Forrest Out-of-sample Predictions"/>
</p>

Expected value of **`MAPE`: 9%**
