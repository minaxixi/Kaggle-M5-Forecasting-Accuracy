# Kaggle-M5-Forecasting-Accuracy
 My solution to the Kaggle competition of M5 Forecasting Accuracy
 
 ## Competition homepage
 https://www.kaggle.com/c/m5-forecasting-accuracy
 
 ## Exploratory data analysis
 - The EDA notebook is included, with highlights on findings of the data
 
 ## Feature engineering and modeling
 - The most important features are lag features, created by a combination of lags, rolling windows, and aggregation functions on sales and prices.
 - The modeling is performed using LightGBM.
 - The hyperparameter tuning is done via 3-fold time-series cross validation.

## Inference
- The final prediction (unit sales of the next 28 days) is conducted via recursive inference.

## Results
- My final submission ranks top 3% among the 5500+ teams and wins me a silver medal!
