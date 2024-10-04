About the Dataset:

# EnergyThe energy consumption and weather data from various cities in Spain are combined to create a multivariate time series forecasting problem. The energy dataset contains features related to the generation of energy from different sources like fossil fuels, wind, and coal. On the other hand, the weather dataset contains features related to various weather metrics such as temperature, humidity, pressure, wind speed, etc._price_prediction.

The code consists of 4 main parts:

- Data loading and feature exploartion: This part uses os and pandas to load, process the data into a dataframe, plotting correlation matrix on both the dataset.
- Preprocessing: Involves getting rid of Null values, selecting features required hour,weekday, month, year from the data and plotting visualization, followed by normalizing and reshaping the data follwed by using The Dickey-Fuller test to check if thr data us stationary
- Model building and training: This part using PCA to select the features necessary,normalizing target variables and then building forecasting models With LSTM.
- We plot the train an validation Mean Absolute Error for each case and also compare the scores across the different models towards the end.
