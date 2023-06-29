### Краткое описание репозитория

Данный репозиторий представляет собой общую папку для хранения моих проектов. На текущий момент (июль 2023) здесь представлено три проекта:
- ЦПТ своими руками (задание)
- Выживание на титанике (контест Kaggle)
- Проверка статистических гипотез (задание)

### Файлы в репозитории:

**Ноутбуки:**
- Central_limit_theorem_via_my_hands.ipynb - питоновский ноутбук, в котором проверяется утверждение центральной предельной теоремы. Из произвольного распределения извлекаются выборки, рассчитываются их средние, и строится распредление выборочных средних.
- DS_Kaggle_Competitions.ipynb - питоновский ноутбук,в котором я строю различные ML-модели для решения задачи о выживании на Титанике. Пробовал модели logit, KNN, DecisionTree, Random Forest, MLP, GBDT (catboost). Пока лучший результат 77%.
- disease_hypo_test.ipynb - ноутбук, в котором реализована статистическая проверка гипотез о заболеваемости в компании. Данные проверяются на нормальность при помощи критерия Шапиро-Вилка, после чего к ним применяется критерий Манна-Уитни для непосредственной проверки гипотез.

**Скрипты:**
- absent_days.py - дашборд, описывающий результат проверки статистических гипотез о заболеваемости в компании (более расширенный функционал по сравнению с соответствующим ноутбуком. Запускается через Terminal при помощи библиотеки Streamlit. На вход требуется csv-файл. Более подробно о формате и требованиям ко входному файлу можно прочитать внутри самого дашборда. Тестовый файл нужного формата имеется в репозитории.

**Файлы с данными:**
- absent_days_test_data.csv - основные данные для ноутбука disease_hypo_test.ipynb / тестовый файл для скрипта (дашборда) absent_days.py

**Прочие файлы:**
-.gitignore
-.readme

   
