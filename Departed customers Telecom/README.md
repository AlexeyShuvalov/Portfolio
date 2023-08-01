# Определение потенциально ушедшего клиента

[ipynb](https://github.com/AlexeyShuvalov/Portfolio/blob/main/Departed%20customers%20Telecom/Departed_customers_Telecom.ipynb)

## Описание проекта

Требуется создать модель предсказания отказа клиента от использования услуг для оператора связи, который и является заказчиком. Данный оператор предоставляет услуги связи абонентам, имеется два основных направления: интернет и телефония. Модель должна предсказывать факт ухода клиента, что позволит заказчику разработать ряд мер по повышению лояльности клиента и таким образом изменить решение клиента об уходе.



## Навыки и инструменты

- **python**
- **numpy**
- **pandas**
- **matplotlib**
- **seaborn**
- **re**
- **math**
- **phik**
- phik.report.**plot_correlation_matrix**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**GridSearchCV**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.ensemble.**RandomForestClassifier**
- Catboost
- sklearn.metrics.**roc_curve**
- sklearn.metrics.**accuracy_score**
- sklearn.metrics.**roc_auc_score**
- sklearn.metrics.**confusion_matrix**
- sklearn.pipeline.**Pipeline**
- sklearn.compose.**ColumnTransformer**

## 

## Общий вывод

Была проведена предобработка данных, составлен портрет уходящего пользователя. Обучили несколько моделей, выбрали модель CatBoost. Были составлены некоторые вопросы/рекомендации к заказчику.
