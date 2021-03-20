# Web_Traffic_Forecast



## **Table of Contents:**
1. [Project Introduction](README.md#project-introduction)
2. [File Description](README.md#file-description)
3. [Libraries used](README.md#libraries-used)
4. [Results](README.md#results)
5. [Licensing, Acknowledgements](README.md#licensing-acknowledgements)

## **Project Introduction**<br/>
  In this project, i have been provided time series data representing a number of daily views of different Wikipedia articles along with the name of the article and type of the traffic this time-series represents like mobile, desktop, spider/crawler & all. Based on the available data, the task at hand is to forecast/predict future traffic to Wikipedia pages. Dataset provided by Kaggle, [here](https://www.kaggle.com/c/web-traffic-time-series-forecasting/data) <br/>

## **File Description** <br/>
  There are two files:<br/>
a) Web_Traffic.zip file contains csv file which has raw data of traffic details of English WikiPedia pages.
b) Web_Traffic_Forecast.ipynb contains complete python code starting from importing csv file to visualization/Exploratory data analysis, preparing data for modeling, fitting various models and evaluating model performance.<br/>

## **Libraries used** <br/>
  Following are the libraries used:<br/>
Numpy<br/>
Pandas<br/>
Matplotlib<br/>
Seaborn<br/>
StatsModel<br/>
Keras<br/>
Scikit Learn<br/>
Fbprophet<br/>
Math<br/>

## **Results** <br/>
  I decomposed the time series data & found our time-series is stationary.<br/>
I fitted three models: SARIMAX, FB Prophet & LSTM. <be/>
Evaluated all models on Root Mean Square Error (RMSE) & SARIMAX model had the lowest RMSE compared to other two.

## **Acknowledgements** <br/>
  I would like to thank Udacity for nanodegree course on Data Science & Kaggle for providing the dataset.

  
  
