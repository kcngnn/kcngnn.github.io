# Portfolio

---

## Product Demand Forecasting

My individual project in which I used a real-life dataset from [Kaggle](https://www.kaggle.com/felixzhao/productdemandforecasting) to do more practice on times series forecasting.

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/kcngnn/Product-Demand-Forecasting)

<div style="text-align: justify">
First, I analyzed and cleaned the dataset - investigating NA values, negative demand values, removing products that do not meet criteria for statistical forecasting: stopped products and new products, etc.

I built four different models (ARIMA/SARIMA, Simple/Double/Triple Exponential Smoothing, Prophet). I compared and extracted forecasts by models of lowest RMSE values for each product because different products have data patterns suitable for different models.

Later, I prepared another file to run the forecast automatically. The forecast user just needs to load data and choose the forecasting periods to generate forecasts and get the lists of products that are not qualified for statistical forecasting (stopped products and new products).</div>

<center><img src="images/product-forecast.PNG"/></center>

---

## Weather Patterns and Forecast in Australia

My individual project in partial fulfillment of the course *Data Mining for Business Analytics*, in which I learnt about Clustering, Association Analysis, a number of classification methods, and text mining.

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/kcngnn/Rain-Prediction-In-Australia)

<div style="text-align: justify">
I employed a weather dataset from Australia’s Bureau of Meteorology, comprised of 142,193 daily weather observations at 49 different
locations all over Australia between 2007 and 2017.
  
First, I performed clustering analysis to find out locations across Australia that have similar weather conditions.

Second, I build a predictive model to forecast the possibility of rain on the following day. I tried three techniques, including k
Nearest Neighbors, Support Vector Machine, and Artificial Neural Networks to get the one with best performance. I continued to use feature selection to improve the model performance.
</div>

<center><img src="images/australia-weather.JPG"/></center>

---
<center>© 2020 Kim-Cuong Nguyen. Powered by Jekyll and the Minimal Theme.</center>
