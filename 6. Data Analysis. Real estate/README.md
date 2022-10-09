
# Предсказание оттока клиентов

## Описание проекта

Необходимо написать модель, которая должна предсказать кто из клиентов, скорее всего, перестанет пользоваться услугами компании. Модель поможет заранее определять таких клиентов, чтобы у компании была возможность попытаться их удержать ("задобрить" промокодами и специальными условиями).

## Навыки и инструменты:

 - **pandas**
 - **pandas_profiling**
 - **phik**
 - **plotly**
 - **optuna**
 - **matplotlib**
 - imblearn.over_sampling.**SMOTE**

sklearn

 - sklearn.model_selection.**train_test_split**
 - sklearn.linear_model.**LogisticRegression**
 - sklearn.metrics.**roc_auc_score**
 - sklearn.metrics.**accuracy_score**
 - sklearn.ensemble.**RandomForestClassifier**
 - sklearn.tree.**DecisionTreeClassifier**
 - sklearn.metrics.**make_scorer**
 - sklearn.model_selection.**cross_val_score**
 - sklearn.metrics.**roc_curve**
 - sklearn.preprocessing.**OneHotEncoder**
 - sklearn.utils.**shuffle**
 - sklearn.dummy.**DummyClassifier**

boosting

 - **lightgbm**
 - **CatBoost**
 - **xgboost**



## Общий вывод

Было обучено несколько моделей, гиперпараметры подбирались с помощью Optuna, что заняло какое-то время, но позволило добиться хороших показателей метрик.
