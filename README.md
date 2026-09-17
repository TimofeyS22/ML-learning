# ML-learning

Работы по машинному обучению на датасете автомобилей.

## Файлы

- [homework_2_linregmethods.ipynb](homework_2_linregmethods.ipynb) — сравнение пяти методов градиентного спуска с TimeDecayLR.
- [sem_2_linreg_methods.ipynb](sem_2_linreg_methods.ipynb) — сравнение постоянного шага и TimeDecayLR для VGD, SGD, SAG, Momentum и Adam.
- [auto_dataset.csv](auto_dataset.csv) — исходные данные, целевая переменная `price`.

В ноутбуках сохранены результаты выполнения, таблицы и графики. В семинарской работе также есть проверки метрик и повторные запуски SGD/SAG с разными seed.

## Запуск

Работы проверены на Python 3.12. Установить зависимости:

```bash
python -m pip install -r requirements.txt
```

Открыть нужный ноутбук в Jupyter или VS Code, выбрать это окружение Python и выполнить все ячейки сверху вниз. Файл `auto_dataset.csv` должен лежать рядом с ноутбуками. Готовые результаты можно просмотреть прямо на GitHub.
