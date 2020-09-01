# Portfolio

---

## Product Demand Forecasting

My individual project in which I used a real-life dataset from [Kaggle](https://www.kaggle.com/felixzhao/productdemandforecasting) to do more practice on times series forecasting.

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/kcngnn/Product-Demand-Forecasting)

<div style="text-align: justify">
First, I analyzed and cleaned the dataset - investigating NA values, negative demand values, removing products that do not meet criteria for statistical forecasting: stopped products and new products, etc. <br/>

I built four different models (ARIMA/SARIMA, Simple/Double/Triple Exponential Smoothing, Prophet). I compared and extracted forecasts by models of lowest RMSE values for each product because different products have data patterns suitable for different models.<br>

Later, I prepared another file to run the forecast automatically. The forecast user just needs to load data and choose the forecasting periods to generate forecasts and get the lists of products that are not qualified for statistical forecasting (stopped products and new products).<br></div>

<center><img src="images/product-forecast.PNG"/></center>
<br>

---

## Weather Patterns and Forecast in Australia

My individual project in partial fulfillment of the course ***Data Mining for Business Analytics***, in which I learnt about Clustering, Association Analysis, a number of classification methods, and text mining.

[![Read Report](https://img.shields.io/badge/Report-Read%20Report-green)](../master/pdf/rain_prediction_in_australia.pdf)[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/kcngnn/Rain-Prediction-In-Australia)

<div style="text-align: justify">
I employed a weather dataset from Australia’s Bureau of Meteorology, comprised of 142,193 daily weather observations at 49 different
locations all over Australia between 2007 and 2017.<br>
  
First, I performed clustering analysis to find out locations across Australia that have similar weather conditions.<br>

Second, I build a predictive model to forecast the possibility of rain on the following day. I tried three techniques, including k
Nearest Neighbors, Support Vector Machine, and Artificial Neural Networks to get the one with best performance. I continued to use feature selection to improve the model performance.<br>
</div>

<center><img src="images/australia-weather.JPG"/></center>
<br>

---

## Supply Chain Analytics Problems

Individual practices of using Python to solve supply chain problems. Most of the problems are self-created with reference to sample ones.

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/kcngnn/Supply-Chain-Analytics)

**Problems:** <br/>
<div style="text-align: justify">
1/ Supply Network Optimization <br/>
<br/>
</div>

<center><img src="images/supply-analytics.JPG"/></center>
<br>

---

## Screening for Chronic Kidney Disease (CKD)

A group project in fulfillment of the course ***Multivariate Analysis***, in which we learnt how to use four techniques, Principle Component Analysis, Factor Analysis, Logistics Regression, and Discriminant Analysis.

[![Read Report](https://img.shields.io/badge/Report-Read%20Report-green)](../master/pdf/screening_for_ckd.pdf)[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/kcngnn/Chronic-Kidney-Disease-Prediction)

<div style="text-align: justify">
Objective: create an easy-to-use screening tool to identify people who run a high risk of CKD so that they can get treatment early - expect to earn $1,300 for a true positive and be penalized by $100 for a false positive. <br/>
  
The team set two priorities for the screening tool. <br/>
- Simplicity: The tool must be simple enough so that our grandparents could well understand to use as well. <br/>
- Accuracy: This is a must. Otherwise, the tool does not make any sense. <br/>
The team ran logistic regression on this dataset a few times to get the final predictive model on probabilities of CKD presence at patients. We first applied backward elimination approach to get the first model, from which we analyzed and defined significant variables that should be included in the screening tools. By narrowing down the number of variables to 9, we ran a reduced model and compared its performance to the first model – the backward elimination one.  <br/>
</div>

<center><img src="images/ckd-model.JPG"/></center>
<center><img src="images/ckd-charts.jpg"/></center>
<br>

---
<center>© 2020 Kim-Cuong Nguyen. Powered by Jekyll and the Minimal Theme.</center>
