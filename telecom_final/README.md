# Отток Клиентов Телеком компании 
  
[ipynb](https://github.com/kormeg/portfolio/blob/main/telecom_final/telecom_final.ipynb)
## Описание проекта  
  
Требуется изучить информацию о пользователях телеком компании. Построить модель для прогноза оттока клиентов. Разобраться в факторах и причинах прекращения пользования услугами компании.
  
## Навыки и инструменты:  
* **python** / **pandas** / **numpy** / **matplotlib** / **seaborn**
* sklearn.tree.**DecisionTreeClassifier**
* sklearn.ensemble.**RandomForestClassifier**
* sklearn.linear_model.**LogisticRegression**
* sklearn.model_selection.**train_test_split** / **GridSearchCV**
* sklearn.preprocessing.**OneHotEncoder** / **OrdinalEncoder** / **StandardScaler**
* sklearn.metrics.**roc_auc_score** / **accuracy_score** / **roc_curve** / **precision_score** / **recall_score** / **f1_score**
* sklearn.compose.**ColumnTransformer**
* sklearn.pipeline.**Pipeline**
* imblearn.over_sampling.**SMOTENC**
* catboost.**CatBoostClassifier**
* lightgbm.**LGBMClassifier**
* **phik**
* **re**

  
  
## Общий вывод  
Была произведена загрузка, обработка и анализ данных, сгенерированы необходимые признаки, заполнены пропуски, произведен анализ распределений признаков, Проведена кроссвалидация с масштабированием количественных и кодированием категориальных признаков и подбором гиперпараметров для 5 моделей. Для лучшей модели произведен анализ вклада каждого отдельного признака в предсказание и проверка на тестовой выборке.
