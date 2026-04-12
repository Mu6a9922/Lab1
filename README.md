# Лабораторная работа №1 — Исследовательский анализ данных (EDA)

## Описание

Исследовательский анализ датасета **Student Mental Health & Burnout** (1 000 000 записей, 20 признаков). Анализ факторов, влияющих на выгорание, ментальное здоровье и риск отчисления студентов.

## Датасет

- **Источник:** [Kaggle — Student Mental Health & Burnout](https://www.kaggle.com/datasets/ayeshasiddiqa123/student-health)
- **Размер:** 1 000 000 строк, 20 столбцов
- **Признаки:** демографические данные, учебная нагрузка, показатели психического состояния, образ жизни, социальные факторы

## Структура проекта

| Файл | Описание |
|------|----------|
| `lab1_eda.ipynb` | Jupyter Notebook с полным EDA |
| `student_mental_health_burnout_1M.csv` | Исходный датасет |
| `README.md` | Описание проекта |

## Выполненные задания

1. Описание предметной области и цели анализа
2. Загрузка и первичный обзор данных (`shape`, `info`, `describe`)
3. Анализ пропусков и выбросов (методы IQR и Z-score)
4. Очистка данных (дубликаты, winsorization, оптимизация типов)
5. Feature engineering (5 новых признаков: `psych_load_index`, `sleep_study_ratio`, `digital_load`, `external_pressure`, `age_group`)
6. Визуальный анализ (гистограммы, boxplot, scatter, heatmap, pairplot, barplot)
7. 7 аналитических выводов

## Технологии

- Python 3.10
- NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, SciPy

## Запуск

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy jupyter
jupyter notebook lab1_eda.ipynb
```
