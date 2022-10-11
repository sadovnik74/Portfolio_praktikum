# Прогнозирование температуры стали
## Описание проекта

Требуется создать модель машинного обучения, прогнозирующую температуру сплава перед подачей его на розлив. В нашем распоряжении были таблицы содержащие данные о замерах температуры, о нагреве сплава, о добавках в сплав и о продувке сплава газом.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **math**
- **matplotlib**
- **seaborn**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**make_scorer**
- sklearn.metrics.**mean_squared_error**
- sklearn.metrics.**mean_absolute_error**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**train_test_split**
- catboost.**CatBoostRegressor**
- xgboost.**XGBRegressor**
- lightgbm.**LGBMRegressor**
- 

## 

## Краткий вывод
Были обучены несколько моделей с подбором гиперпараметров. Лучшее качество показала модель `CatBoostRegressor`, MAE=6.19. 
Анализ важности признаков показал, что для прогноза наиболее важны начальная температура сплава и энергия нагрева.
