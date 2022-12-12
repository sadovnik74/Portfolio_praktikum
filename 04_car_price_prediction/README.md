# Определение стоимости автомобилей
## Описание проекта

Целью нашего проекта был поиск модели,  которая будет рекомендовать стоимость автомобиля в зависимости от его характеристик и других факторов.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- **time**
- functools.**partial**
- **datetime**

- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_squared_error**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.model_selection.**train_test_split**
- sklearn.ensemble.**RandomForestRegressor**
- sklearn.linear_model.**LinearRegression**
- lightgbm.**LGBMRegressor**
- sklearn.preprocessing.**StandardScaler**
- sklearn.preprocessing.**OrdinalEncoder**
- sklearn.preprocessing.**OneHotEncoder**

## Краткий вывод
Мы изучили данные из базы объявлений о продаже автомобилей и выполнили предобработку данных.
Построили модель градиентного бустинга LightGBM при помощи случайной оптимизации гиперпараметров и для сравнения взяли две более простые модели: Случайный лес и Линейная регрессия.
Сравнение моделей показало, что лучшей моделью для решения нашей задачи будет LightGBM с  оценкой RMSE = 1649 евро, потому что она обеспечивает лучшее качество предсказаний и лучшее время обучения.
 
