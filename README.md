Скрипт парсит отзывы с сайта tripadvisor.ru, агрегируя результаты в CSV-файл.

В выборку попадают - дата отзыва, имя пользователя, возраст и пол пользователя(если указаны), оценка месту, заголовок и текст отзыва.
![Alt text](images/results.png?raw=true "Usage example")

Запуск - python scrap.py input.csv

На вход скрипт принимает csv файл с параметрами в формате:

name,http-url,list_count

где name - будущее имя файла для хранения результатов парсинга, http-url - ссылка на первую страницу места, list_count - кол-во страниц, с которых будет собираться информация.
![Alt text](images/example.png?raw=true "Usage example")