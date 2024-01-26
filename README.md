# Car price prediction
Данный проект демонстрирует, как можно представлять ML-решения в виде веб-приложения. ML-модель обучилась на [данных о подержанных автомобилях в некоторой стране](https://raw.githubusercontent.com/evgpat/stepik_from_idea_to_mvp/main/datasets/cars.csv) предсказывать стоимость машин. 

Само приложение можно найти [здесь](https://car-price-pred.streamlit.app/).

## Файлы
- `app.py`: файл приложения streamlit
- `scaler.pickle`: сохраненный скалер, который масштабирует данные, введенные пользователем, чтобы модель работала корректно
- `requirements.txt`: файл, в котором прописаны все использующиеся в проекте библиотеки
- `model.pickle`: сохраненная предсказательная модель
- `EDA_cars.ipynb`: ноутбук, в котром производилась предварительная обработка данных, анализ показателей и подбор модели

## Технологии
Модель машинного обучения, использующаяся в данном проекте, основывается на методе случайного леса, реализация которой взята из библиотеки 'scikit-learn'. Для создания веб-приложения была задействована библиотека 'streamlit'. Исследовательский анализ данных и подбор модели проходили в 'google colab'. 
