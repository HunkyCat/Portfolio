
# Улучшение процесса обогащения золота

## Описание проекта

Требуется подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

## Навыки и инструменты:

 - **python**
 - **pandas** 
 - **numpy** 
 - **plotly**
 - plotly.**express**
 
 sklearn
 
 - sklearn.metrics.**mean_absolute_error**
 - sklearn.ensemble.**BaggingRegressor**
 - sklearn.model_selection.**cross_val_score**
 - sklearn.metrics.**mean_squared_error**
 - sklearn.ensemble.**RandomForestRegressor**
 - sklearn.linear_model.**LinearRegression**
 - sklearn.dummy.**DummyRegressor**
 
 boosting
 
 - **catboost** 


## Общий вывод

Было проведено обучение выбранных моделей для стадий грубой и тонкой очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.
