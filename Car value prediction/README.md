# Определение стоимости автомобилей

[ipynb](https://github.com/AlexeyShuvalov/Portfolio/blob/main/Car%20value%20prediction/Car_value_prediction.ipynb)

## Описание проекта


Целью данной работы является создание модели предсказания цены автомобиля для приложения сервиса по продаже авто. Необходимо учесть качество модели (RMSE), а также скорость обучения и предсказания.



## Навыки и инструменты

- **numpy**
- **pandas**
- **matplotlib**
- **seaborn**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.linear_model**Ridge**
- sklearn.metrics.**mean_squared_error**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**cross_val_score**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.impute.**KNNImputer**
- **lightgbm**
- sklearn.ensemble.**AdaBoostRegressor**


## 

## Общий вывод

Была проведена тщательная предобраюотка данных, были обучены модели AdaBoost, RandomForest, модель LightGBM. Более точной оказалась модель LGBM, однако по скорости предсказания лидирует RandomForest (при этом не сильно теряя в качестве). Выбрали LightGBM.

