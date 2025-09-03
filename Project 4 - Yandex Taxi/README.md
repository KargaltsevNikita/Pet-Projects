# Pet-проект Яндекс Такси - прогнозирование количества заказов такси на следующий час

## Описание проекта
Помочь сервису «Яндекс Такси» создать модель для прогнозирования количества вызовов такси.

## Навыки и технологии
#### Теги: временные ряды, регрессия, машинное обучение
![statsmodels](https://img.shields.io/badge/statsmodels-black?style=flat&logoColor=orange)
![LightGBM](https://img.shields.io/badge/LightGBM-black?style=flat&logo=lightgbm&logoColor=orange)
![Pandas](https://img.shields.io/badge/Pandas-black?style=flat&logo=pandas&logoColor=orange)
![NumPy](https://img.shields.io/badge/NumPy-black?style=flat&logo=numpy&logoColor=orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-black?style=flat&logo=matplotlib&logoColor=orange)
![Seaborn](https://img.shields.io/badge/Seaborn-black?style=flat&logo=seaborn&logoColor=orange)

## Сферы деятельности
Бизнес, Интернет-сервис

## Основные пункты исследования
- Подготовка данных
- Исследовательский анализ данных
- Обучение модели
- Анализ модели

## Результаты
- Добились значения 39.68 для метрики RMSE на тестовой выборке

## Выводы
- При предсказание пиковых часов с заказами, модель дает предсказания с 'задержкой'
- Модель пропускает некоторые пиковые значения
- Из-за задержек в предсказание максимумов, может произойти наложение - когда по прогнозу должен быть максимум в этот час, в реальности будет минимум
