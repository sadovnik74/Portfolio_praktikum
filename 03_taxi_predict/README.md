# Прогнозирование заказов такси
## Описание проекта

Нужно спрогнозировать количество заказов такси на следующий час. 

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **time**
- functools.**partial**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- **statsmodels.api**

- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_squared_error**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**train_test_split**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.linear_model.**LinearRegression**
- catboost.**CatBoostRegressor**
- lightgbm.**LGBMRegressor**

## Краткий вывод
Для обучения моделей были созданы признаки путём сдвига данных, добавления скользящего среднего и создания признаков содержащих день, день недели и месяц. Затем было произведено обучение с подбором гиперпараметров нескольких моделей: LinearRegression, RandomForestRegressor, CatBoostRegressor.

Лучшей моделью получилась модель LinearRegression с  оценкой RMSE = 36.54
