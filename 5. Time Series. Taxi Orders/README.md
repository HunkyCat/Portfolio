
# Прогнозирование заказов такси

## Описание проекта

Необходимо написать модель, которая будет предсказывать количество заказов такси на следующий час, основываясь на исторических данных.

## Навыки и инструменты:


 - **pandas**
 - **datetime**
 - statsmodels.tsa.seasonal.**seasonal_decompose**
 - plotly.**express**
 - matplotlib.**pyplot**

sklearn

 - sklearn.model_selection.**train_test_split**
 - sklearn.linear_model.**LinearRegression**
 - sklearn.metrics.**mean_squared_error**
 - sklearn.model_selection.**GridSearchCV**
 - sklearn.metrics.**make_scorer**
 - sklearn.ensemble.**RandomForestRegressor**
 - sklearn.tree.**DecisionTreeRegressor**
 - sklearn.dummy.**DummyRegressor**
 - sklearn.model_selection.**TimeSeriesSplit**

boosting
 
 - **lightgbm**
 - **catboost**


## Общий вывод

Предсказания модели работают, однако иногда модель не способна уловить резкие изменения кол-ва заказов.

### Статус проекта
Завершен
