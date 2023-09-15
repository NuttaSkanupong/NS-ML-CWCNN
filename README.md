# NS-ML-CWCNN
This code was developed for the paper "Machine Learning for Multiple Decade PDO Forecasts". 
The goal is to use deep learning to predict PDO occurrences by using Keras and Tensorflow.
1.	Data_preprocessing.ipynb: Downloading and preparing the data before training the model
2.	Example_of_the_tuning_process_using_ensemble_CMIP6.ipynb: Determining the hyperparameters to employ for the subsequent training
3.	Channel-wise-based_CNN_second_trainning.ipynb: Training the model with the best architecture and predicting the PDO
4.	Channel-wise-based_CNN_all-season_correlation.ipynb: Analyzing the all-season correlation of our model compared with other methods
5.	Channel-wise-based_CNN_predicted_PDO_for_heatmap_analysis.ipynb: Predicting PDO in each target month by using different channel-wise-based CNN models
6.	Channel-wise-based_CNN_predicted_world_SST_for_heatmap_analysis.ipynb: Training the model for analyzing heatmaps in several oceans.
7.	Channel-wise-based_CNN_the_time_series_of_PDO_index.ipynb: Plotting the time series of the PDO index predicted from the model
8.	Correlation_seasonal_heatmaps_and_RMSE_maps.ipynb: Plotting the seasonal heatmap and RMSE maps during positive and negative phases
9.	Hit_rate_of_PDO_type_prediction.ipynb: Evaluating the model's ability to predict PDO type
10.	Heatmap_interpretation.ipynb: Indicating how each predictor's impact on the predictand at each grid point
11.	Analyzing_SSTA_and_wind_anomalies_corresponds_to_PDO.ipynb: Plotting the SSTA and wind anomalies corresponds to the PDO events.
12.	requirements.txt: The Anaconda environment was used in this paper.
