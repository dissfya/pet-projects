# A/B test

## Оглавление

[1. Основные цели и задачи проекта](https://github.com/dissf/pet-projects/blob/main/data_analytics/ab_test/README.md#Основные-цели-и-задачи-проекта)  
[2. Краткая информация о данных](https://github.com/dissf/pet-projects/blob/main/data_analytics/ab_test/README.md#Краткая-информация-о-данных)  
[3. Полезные библиотеки](https://github.com/dissf/pet-projects/blob/main/data_analytics/ab_test/README.md#Полезные-библиотеки)

### Основные цели и задачи проекта

Идея A/B тестирования очень проста. Пользователи ресурса случайным образом делятся на сегменты. Один из сегментов остается без изменений — это контрольный сегмент “A”, на основе данных по этому сегменту мы будем оценивать эффект от вносимых изменений. Пользователям из сегмента “B” показываем измененную версию ресурса.
Имеется датасет, в нем представлены результаты, где пользователи сайта просмотрели старую и новую веб-страницу.
Целью этого теста было определить, влияет ли новая веб-страница на увеличение числа конверсии по сравнению со старой.

### Краткая информация о данных

Датасет содержит информацию о проведенном a/b тесте.
Датасет представлен в [репозипории](https://github.com/dissf/pet-projects/blob/main/DA_DS/ab_test/ab_data.csv).  
Описание полей датасета **df**:

* **user_id** - id пользователя
* **timestamp** - время и дата посещения сайта
* **group** - принадлежность пользователя к определенной группе(контрольной и экспериментальной)
* **landing_page** - версия страницы, которую видит пользователь
* **converted** - говорит о том, сделал ли пользователь покупку

### Полезные библиотеки

* pandas
* numpy
* scipy
