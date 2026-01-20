# house-prices
Предсказание цен на жилье с помощью градиентного бустинга
### Стэк технологий
**Препроцессинг:** pandas, numpy — подготовка данных, вычисления.

**Машинное обучение:** CatBoost — градиентный бустинг, самостоятельно обрабатывает категориальные признаки.

**Валидация модели:** scikit-learn — разделение данных на train/val, вычисление метрики.

**Визуализация:** matplotlib — построение кривой обучения.

### Результаты

![Кривая обучения](images/learning-curve.png)

### Запуск проекта
1. Клонирование репозитория
	```bash 
	git clone https://github.com/sofiachuleva/house-prices.git
    cd house-prices
	```
2. Датасет
    
    Скачайте датасет с Kaggle по ссылке: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data.

    Поместите файлы `train.csv` и `test.csv` датасета в папку `data/` внутри репозитория
3. Создание виртуального окружения
    ```bash 
	python -m venv venv
	```
4. Активация окружения

    Для Mac/Linux:
    ```bash 
    source venv/bin/activate
    ```
    Для Windows:
    ```bash 
    venv\Scripts\activate
    ```
5. Установка зависимостей
    ```bash 
    pip install -r requirements.txt
    ```
6. Запуск Jupyter Notebook
    ```bash 
    jupyter notebook
    ```
    Далее, откройте `house-prices.ipynb` и запустите все ячейки.
