# Time series forecasting for annual power consumption and carbon emission-
Time series forecasting for annual power consumption and carbon emission in different Countries/Areas. 

Data source: https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy

The dataset contains annual data from over 150 countries/areas (in the dataset are called Entities) worldwide about many different aspects such as power consumption, carbon emission, GDP, etc.

To predict power consumption and carbon emission for each Entity, time series forecasting models will be used in combination with time series observations in the dataset, univariate time series models will only use target past data to predict and multivariate will use all provided observations (feature engineering may be improved later to increase performance)
Currently built models (will continue to test new models in the future):
* LSTM (Long short-term memory) encoder-decoder for Univariate time series (UTS)
* LSTM encoder-decoder for Multivariate time series (MTS)
* Facebook prophet for UTS
* Facebook prophet for MTS (using add_regressor)
* Neural prophet for UTS (3 lags AR window)
* Neural prophet for MTS (3 lags AR window for both target and other observations)

Results predictions for 3 Countries, Algeria, Australia, Canada:


