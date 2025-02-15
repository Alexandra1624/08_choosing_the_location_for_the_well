# Выбор локации для скважины


[ipynb](https://github.com/Alexandra1624/08_choosing_the_location_for_the_well/blob/main/08_choosing_the_location_for_the_well.ipynb)

## Описание проекта

Предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Необходимо постройть модель для определения региона, где добыча принесёт наибольшую прибыль. 


## Навыки и инструменты

- ![](https://img.shields.io/badge/-Python-bgreen)
- ![](https://img.shields.io/badge/-Pandas-blue)
- ![](https://img.shields.io/badge/-Nympy-B8860B)
- ![](https://img.shields.io/badge/-Matplotlib-violet)
- ![](https://img.shields.io/badge/-Scikit--learn-808000)
- ![](https://img.shields.io/badge/-Bootstrap-712F26)

## Вывод

Обучение модели проводилось с помощью ***линейной регрессии***.

Лучшее ***RMSE*** было выявлено в регионе 1.

Расчет прибыли и рисков показал, что суммарный запас сырья в 200 лучших скважинах и прибыль получились для региона 0. 30183.55 тыс.баррелей и 3582.60 млн.рублей соответственно.

С помощи техники ***Bootstrap*** с 1000 выборок было найдено распределение прибыли в трех регионах. Наиболее выгодный для разработки скважин оказался регион 1. У него минимальные риски 1.30% и максимальная средняя прибыль: 446.20 млн.руб.

Наилучший результат был получен при увеличении выборки для ***Случайного леса***. 
