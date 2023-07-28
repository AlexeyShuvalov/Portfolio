# Прогнозирование заказов такси

[ipynb](https://github.com/AlexeyShuvalov/Portfolio/blob/main/Cab%20order%20forecast/%D0%A1ab_order_forecast.ipynb)

## Описание проекта

Необходимо разработать модель, которая будет предсказывать количество заказов такси на один час вперед. Модель необходима для увеличения числа водителей в период пиковой нагрузки.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **scipy**
- **matplotlib**
- **seaborn**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.linear_model.**Ridge**
- sklearn.metrics.**mean_squared_error**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**TimeSeriesSplit**
- **catboost**
- **Prophet**


## 

## Общий вывод 

Были созданы дополнительные признаки в наших данных и обучено несколько моделей. Для теста была выбрана модель Catboost. Она позволила добиться требуемого показателя RMSE.

