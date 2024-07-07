
## The project

This dataset is extracted from the following Kaggle competition : [https://www.kaggle.com/competitions/optiver-trading-at-the-close/overview](https://www.kaggle.com/competitions/optiver-trading-at-the-close/overview) . 

Kaggle competition brief : 
This dataset contains historic data for the daily ten minute closing auction on the NASDAQ stock exchange. Your challenge is to predict the future price movements of stocks relative to the price future price movement of a synthetic index composed of NASDAQ-listed stocks.

This is a forecasting competition using the time series API. The private leaderboard will be determined using real market data gathered after the submission period closes.

The objective of this project is to create a proof of concept of the use of mlflow without autlog with optuna, and best model extraction from mlflow.

<br>

![](images/mlflow_tab.JPG) 

<br>

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/sklearn-white?logo=scikit-learn)](#) [![](https://img.shields.io/badge/Google-white?logo=mlflow)](#) [![](https://img.shields.io/badge/Optuna-white?logo=data:image/png;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAgGBgcGBQgHBwcJCQgKDBUODAsLDBkSEw8VHhsgHx4bHR0hJTApISMtJB0dKjkqLTEzNjY2ICg7Pzo0PjA1NjP/2wBDAQkJCQwLDBgODhgzIh0iMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzMzP/wAARCAAKAAoDASIAAhEBAxEB/8QAFgABAQEAAAAAAAAAAAAAAAAABgME/8QAIxAAAgECBQUBAAAAAAAAAAAAAQIDABEEBhIhQQUTIjFScf/EABQBAQAAAAAAAAAAAAAAAAAAAAT/xAAZEQEAAwEBAAAAAAAAAAAAAAABAAIDESH/2gAMAwEAAhEDEQA/AF4xEnU0lx2NOqVm8Q1/Df0Pm1aoetZl7KdqWVo9I0sYQxI4NyN/2q5ghiGcoYhGgjlZDImkWcn2SOafgBQFUAKNgBxTNLlQeQWWa2fZ/9k=)](#) [![](https://img.shields.io/badge/Dagshub-white?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAAKCAMAAAC67D+PAAAAIGNIUk0AAHomAACAhAAA+gAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAADeUExURfT19fj5+f///6KWlpmHiOTk5P7+/svFxcjBwbSen5VLToFjZLi3t9vc2+Pj4ubm5qGfn4FWV8CrrNvR0ZpVWHRAQmRfX3Nzcs3Lw4yMillMTIVPUdzS0vn5+a6RkmZRUmRkZG9vb9jWzYeGhF1aWol6e/f29sDAwGRjY1FRUWlpZ4WEgU9PT5WVlb+/v2NjY39+e768tKWjnLa0rIWEgKenp9nZ2ZGRjfPw5Pv466+upuXi1vbz5tva1vv7/Nvb2OXj29rZ0tHPx9fVz+Ph2uXk4ff39/Ly8fj4+P39/nQBThAAAAABYktHRAJmC3xkAAAAB3RJTUUH5wsdFQI7i+bV9AAAAAFvck5UAc+id5oAAABrSURBVAjXY2BgZIICBmYWVhDNxs7BwMnFzcPLxy8gKMQgLCIqJi4hKSUtwyArJ6+gqKSsoqrGwKSuoamlpK2jy8TApKdvYGhkbGIKZJqZW1haWdvYsjEw2dk7ODo5u7gCRZmY3Nzc3Tw8mQCpNAtuwFWNdgAAACV0RVh0ZGF0ZTpjcmVhdGUAMjAyMy0xMS0yOVQyMTowMjo1MyswMDowMM8jN1kAAAAldEVYdGRhdGU6bW9kaWZ5ADIwMjMtMTEtMjlUMjE6MDI6NTMrMDA6MDC+fo/lAAAAKHRFWHRkYXRlOnRpbWVzdGFtcAAyMDIzLTExLTI5VDIxOjAyOjU5KzAwOjAwTRvxdAAAAABJRU5ErkJggg==)](#)

Skills developed: Model optimization 

Link : [US_stocks_prediction_project](https://github.com/petoulemonde/petoulemonde.github.io/tree/main/docs/US_stocks_prediction_project)

----
## Data description

The dataset used in this project is available here : https://www.kaggle.com/competitions/optiver-trading-at-the-close/data?select=train.csv .

----
## Project Board

2023-11-26 : 
- Notebook finished
- Add images in readme
- Add package images

2023-11-23 : Creation of readme
  
2023-11-22 : Project creation
- Creation of notebook

----
## Future work

1. RandomForstRegressor & GradientBoostingRegressor don't look like good models to predict. Test with NN, auto-ML solution and xgboost, lightGBM and catboost.