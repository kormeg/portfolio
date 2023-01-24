# Отток Клиентов банка  
  
[ipynb](https://github.com/kormeg/portfolio/blob/main/churn_ml_classification/churn_ml_classification.ipynb)
## Описание проекта  
  
Требуется спрогнозировать, уйдёт клиент из банка в ближайшее время или нет на основе исторических данных о поведении клиентов и расторжении договоров с банком, построить модель с предельно большим значением F1-меры. Преодолеть порог 0.59 на тестовой выборке
  
## Навыки и инструменты:  
* **python** / **pandas** / **numpy** / **matplotlib**  
* sklearn.tree.**DecisionTreeClassifier**
* sklearn.ensemble.**RandomForestClassifier**
* sklearn.linear_model.**LogisticRegression**
* sklearn.model_selection.**train_test_split**
* sklearn.preprocessing.**MinMaxScaler**
* sklearn.metrics.**roc_auc_score** / **precision_score** / **recall_score** / **f1_score**


  
  
## Общий вывод  
Было проведено исследование на предмет поиска наиболее подходящей модели машинного обучения. В ходе исследования было протестировано 3 различных типа моделей на двух выборках. Была произведена оптимизация путем подбора гиперпараметров: глубины и количества деревьев, а так же балансировки классов и подбора порога классификации.  

Необходимое значение основной метрики качества было достигнуто.
