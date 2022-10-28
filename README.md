# Progetto-Machine-Learning

For this project me and three colleagues of mine tried to forecast the price of energy in Spain using the KNIME platform, training four different models, Random Forest, XGBoost, ARIMA and LSTM on hourly energy production data of different sources from 2015 to 2018, and then we compared their performances. 

- Check out the [report](https://github.com/Paseen/Progetto-Machine-Learning/blob/main/Report.pdf) 
# Data cleaning
From the dataset all the columns containing only zeros and missing values have been removed.

# Random Forest and XGBoost
The dataset has been divided in training set, which was composed by the 67% of the whole records, and the test set, composed by the remaining percentage. Afterwards a 10-folds cross validation has been performed. 
<br><br>
The best performing model was XGBoost, and its performaces on the test set were: 

|   |XGBOOST   |
|---|---|
|R<sup>2</sup>   |0.81   |
|MAE   |4.50   |
|RMSE   |6.23   |
|MAPE   |0.1   |


# ARIMA and LSTM

|   | ARIMA  |LSTM   |
|---|---|---|
|MAE   |10.59   |3.99   |
|RMSE   |12.79   |4.74   |
|MAPE   |0.18   |0.06 |

For a more in-depth analysis of our group project check the "report.pdf" file in this repository.

Credits to: Greta Gravina, Alessio Pasinato, Niccolò Rocchi, Marco Scatassi.
