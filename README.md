# Final Exam Machine Learning — Острикова Мария

## Цель проекта
- Регрессия: линейная регрессия с нуля (градиентный спуск).
- Классификация: логистическая регрессия с нуля + сравнение с Decision Tree (sklearn).

## Данные
- Файл: Feature-Race.csv
- Источник: (https://www.kaggle.com/datasets/alarchemn/formula-2-dataset?select=Feature-Race.csv)
  
Коротко о полях:
- POS - позиция финиша (целевая переменная).
- LAPS, KPH, LAP, ROUND - числовые признаки.
- TEAM, CIRCUIT - категориальные признаки.

## Постановка задач
- Регрессия: предсказать POS по признакам (LAPS, KPH, LAP, ROUND + TEAM/CIRCUIT).
- Классификация (binary): Top-10 vs Not Top-10, где y = 1 если POS <= 10, иначе 0.
  Сравниваются: Logistic Regression (from scratch) и Decision Tree (sklearn).

## Как запустить
1) Открой ноутбук в Google Colab.
2) Загрузи Feature-Race.csv (через upload) и запусти Run All.
