# Улучшение процесса обогащения золота

[ipynb](https://github.com/AlexeyShuvalov/Portfolio/blob/main/Gold/Gold.ipynb)

## Описание проекта

Требуется подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **scipy**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_squared_error**
- sklearn.metrics.**mean_absolute_error**
- sklearn.preprocessing.**StandardScaler**
- sklearn.impute.**KNNImputer**
- sklearn.linear_model.**LinearRegression**
- statsmodels.stats.outliers_influence.**variance_inflation_factor**
- **matplotlib**

## 

## Общий вывод

Было проведено обучение выбранных моделей для стадий грубой и тонкой очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.
