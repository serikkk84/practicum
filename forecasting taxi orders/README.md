# Прогнозирование заказов такси


## Данные

В наличии исторические данные о заказах такси в аэропортах за 5 месяцев 2018 года.

## Задача

Обучить модель, способную предсказывать количество заказов для компании такси с целью привлечения большего количества водителей в пиковый период. Контрольной метрикой является RMSE с показателем не более 48. 

## Используемые библиотеки
- *pandas*
- *matplotlib*
- *numpy*
- *catboost*
- *lightgbm*
- *sklearn*
- *statsmodels*

## Вывод

Лучшей моделью стала Линейная регрессия. Показатель RMSE на тестовой выборке составил менее 46.
