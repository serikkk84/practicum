# Восстановление золота из руды


## Данные

В наличии данные технологического процесса по восстановлению золота из золотосодержащей руды:
-исходное сырье
-флотационные реагенты: Xanthate, Sulphate, Depressant
--флотация
-отвальные хвосты
-флотационная установка
-очистка
-черновой концентрат золота
-финальный концентрат золота
-объём воздуха
-уровень жидкости
-размер гранул сырья
-скорость подачи

## Задача

Создание прототипа модели машинного обучения для оптимизации производства по восстановлению золота из руды


## Используемые библиотеки
- *pandas*
- *matplotlib*
- *numpy*
- *seaborn*
- *sklearn*

## Вывод

Лучшей моелью для предсказания результатов стала - RandomForestRegressor, кроме того стало известно, что по мере прохождения этапов обработки сырья концентрация золота и свинца увеличивается, в то время как концентрация серебра уменьшается
