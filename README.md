# optimization-of-rolling-shop-load
ИИ оптимизирует производство атомного топлива (Росатом)

# Как пользоваться
Для обучения необходимо в директорию с неросетью положить 3 файла:
ovens_done.csv - информация о печах
series_done.csv - информация о деталях и необходимых операциях с ними за день
answer_done.csv - оптимизированная смена

-- Как превратить файл с оптимизированной сменой в excel файл
необходимо запустить скрипт graph.py

# генерация файлов series_done.csv и oven_done.csv 
1) Зайдите в попку с проектом
2) Убедитесь что у вас есть файл ПланОМД.xlsm
3) Установите на компьютер любую систему для запуска .ipynb
4) Запустите dataframe_preprocessing.ipynb
5) В итоге должны получится два этих файла

# генерация файла answer_done.csv из excel
аналогично series_done.csv и oven_done.csv только убедитесь что на последнем листе есть ответы макроса

# data_structure.ipynb
содержит недоделанные скрипты других вариантов решения
