The objective was to build a model for a car sales company. The important attributes considered were the quality of the predictions, the speed of the prediction, and the time required for training. 

This type of modeling requires feature engineering. I used scikit learn libraries to preprocess the dataset. I used an ordinal encoder for the categorical columns when training random forest, and one-hot-encoding for linear regression, LGB, and Catboost. Below is a snippet of the comparison: 
### Original
![image](https://github.com/hgharris03/TripleTenProjects/assets/106608681/5d1dcd38-6afb-4e27-a340-bb1e4105ec78)

### Ordinal encoder
![image](https://github.com/hgharris03/TripleTenProjects/assets/106608681/1d25a84c-4da9-45d0-9bfe-4b29c8eea480)

I compared random forest, linear regression, LightGBM, and CatBoost. The metric for comparison was mean-squared error. The time it took to train the models were also factored into the conclusion. 

In conclusion, the time to train and predict for the random forest model was 1 min 12s, linear regression was 21s, LGB model was 10.7s, and catboost was 49.7s. Once the parameters were set the LGB model had a faster run time. However, the CatBoost model had a slightly lower MSE score. Overall, I would recommend LGB to be the better model because it is the fastest model to fit and predict the data, and the error is not compromised by the speed.
