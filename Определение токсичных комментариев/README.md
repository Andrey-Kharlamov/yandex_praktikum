# Определение токсичных комментариев

Интернет-магазин запустил новый сервис, в котором пользователи могут осавлять комментариии о товарах. 
Для разработки инструмента по классификации комментариев на токсичные и позитивные было обучено несколько моделей машинного обучения, 
которые использовали различные методы по обработке текстов (bag of words, TF-IDF с N-граммами и без). Оценка модели происходила по метрике: F1-мера.
Наилучший результат показала модель SVC с использованием TF-IDF и биграммой (F1 = 0.795). 

## В проекте был использован следующий стек:
* Pandas
* Numpy
* Sklearn
* NLTK
