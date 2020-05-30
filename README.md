# Курсовая работа студента 2 курса Фундаментальной и прикладной лингвистика Кузнецова Григория Андреевича на тему Фонология каратинского языка: от словарных данных к обобщениям.
## Работа программы
Программа получает на вход текстовый файл 'karata_work.html' в формате HTML.
На выходе программа создает таблицы с данными в формате CSV
Программа написана в среде Jupyter notebook, поэтому для открытия кода необходимо использовать эту среду
### Считывание и подготовка данных
Программа считывает текстовый файл построчно. Каждая строка - словарная статья для одного слова. Далее она делит строку на компоненты при помощи библиотеки BeautifulSoup и заносит их в таблицу. Реализована функция для перевода лемм в формат IPA.
### Анализ данных
В ходе работы программа берет данные из созданных таблиц при помощи различных методов библиотеки pandas. Для каждого элемента анализа (инициали, финали, интервокальные кластеры итд) создается график при помощи библиотеки matplotlib. 
