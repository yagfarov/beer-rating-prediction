# Beer Rating Prediction

Проект посвящён сравнительному анализу различных методов предсказания оценки вкусности пива на небольшом наборе данных. В рамках проекта реализованы следующие подходы:

- CatBoost
- Bagging
- Stacking

## Данные

Используется файл `beer_rew.csv`, содержащий оценки пива и признаки для предсказания. Набор данных небольшой, поэтому результаты носят демонстрационный характер.

## Структура проекта

- `main.ipynb` — Jupyter Notebook с кодом обучения моделей и анализа результатов.  
- `requirements.txt` — зависимости проекта.  
- `beer_rew.csv` — исходные данные.  
- `venv/` — локальное виртуальное окружение.  
- `catboost_info/` — метаданные CatBoost.  

## Установка и запуск

1. Клонируйте репозиторий:

git clone https://github.com/yagfarov/beer-rating-prediction.git
cd beer-rating-prediction

2. Создайте виртуальное окружение и установите зависимости:

python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

Автор
Рустам Ягфаров
