# Классификация комментариев

[ipynb](https://github.com/AlexeyShuvalov/Portfolio/blob/main/Comment_classification/%D0%A1omment_classification.ipynb)

## Описание проекта

Целью работы является построение модели, которая могла бы классифицировать комментарии пользователей интернет-магазина на позитивные и негативные. Качество модели необходимо будет измерять метрикой F1.



## Навыки и инструменты

- **numpy**
- **pandas**
- **re**
- sklearn.model_selection.**train_test_split**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**accuracy_score**
- sklearn.metrics.**recall_score**
- sklearn.metrics.**precision_score**
- sklearn.metrics.**f1_score**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.linear_model.**LogisticRegression**
- **tqdm**
- scipy.sparse.**hstack**
- **fasttext**
- **torch**
- **transformers**

## 

## Общий вывод 

Была проведена пошаговая предобработка исходного текста, после обучили несколько моделей: TF-IDF, fastText и BERT (с тонкой настройкой параметров). Также попробовали в деле предобученную модель с HuggingFace. Лучшего качества (при минимальных временных затратах) удалось достичь с помощью библиотеки fastText.
