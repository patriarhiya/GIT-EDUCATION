<h1 style="text-align: center; font-size: 50px; font-weight = bold;"><b>Инструкция Pyhton</b><h1>

Отступы важны (таб или 4 пробела)
Индексация бывает обратной с минусом, также начало : конец : шаг. 
Присваивания a, b = 1, 2
Модули хранят функции (через import модуль (можно добавить as новое название) - тогда вызов модуль.функция, можно вызвать напрямую from модуль import функция(или *))

## Вначале
Создаем папку. Создаем файл с расширением .py и запускаем терминал. Для создания окружения (чтобы проекты не пересекались) вводим "python3 -m venv folder"

## Переменные
| Переменная | Описание |
|-|-|
|int|целое число|
|float|дробное число|
|bool|булевая|
|str|строка в любых кавычках|
|*var_name* = None|объявляем пустую переменную без типа|
|list = []|создание списка|
|tuple = ()|создание неизменяемого  списка (или кортежа) - в конце всегда запятую|
|dict = {}|создание словаря в скобках (ключ: значение) - ключ вместо индекса|
|set = {}|создание множества в скобках через запятую (множество содержит уникальные значения)|

## Операции
| Операция | Описание |
|-|-|
|+ - *|сложить, вычесть, умножить|
|/|деление по умолчанию в вещественных числах|
|//|целочисленное деление|
|%|остаток от деления|
|str|строка в любых кавычках|
|*var_name* = None|объявляем пустую переменную без типа|
|**|в степень|
|знак=|операция с самим собой|
|a, b, c = tuple |значения из кортежа добавятся в переменные |


## Функции
| Функция | Описание |
|-|-|
|type()|выводит тип переменной|
|print()|выводит на печать, переменные можно через запятую или через + (складывает или соединяет) |
|print(f"{a} {b}")|выводит на печать переменные|
|print("{0} {1}".format(a, b))|выводит на печать переменные в функции format|
|input()|вводит данные, в скобках можно указать текст перед вводом|
|int(), str()|привидение к типу переменных|
|.split() | разделение строки в список |
|sort()|сортировка |
|sorted()|сортировка символьных значений|
|max()|максимальное число из двух|
|map()|подмена значений по функции в агрументе 1- функция, 2- данные|
|filter()|фильтр 1- функция, если истинна, то значение вернется, 2- данные|
|zip()|на вход списки, возвращает список в кортежах по индексу из каждого списка|
|enumerate()|на вход список, возвращает список в кортежах с автоиндексом|
|round()|округение, сначала число, после запятой сколько знаков |
|range()|автозначения 1- начало, 2- конец (не включая) 3- шаг|
|len()|длина строки или массива|
|значение in переменная|проверяет, есть ли данное значение в переменной|
|i.lower() (upper)|в нижний (верхний) регистр|
|i.replace()|1- меняем на 2-|
|list()|список (при печати вначале ставится *, чтобы не было скобок)|
|список.append()|добавить 1- значение в конец списка|
|список.insert()|добавить 1- в индекс 2- значение|
|список.pop()|удалить в конце списка или 1- по индексу|
|tuple()|создание кортежа или преобразование в кортеж |
|dict()|создание словаря|
|del словарь[ключ]|удалить из словаря значение по ключу|
|словарь.items()|обращение ко всем элементам словаря (item это обращение к ключу)|
|словарь.values()|получение значений из словаря|
|множество.add|добавить в множество|
|множество.remove|удалить из множества|
|множество.discard|удалить из множества с проверкой, есть ли такое значение|
|множество.clear|очистить множество|
|set()|создание множества|
|множество.copy()|скопировать множество|
|множество1.union(множество2)|объединение множеств|
|множество1.intersection(множество2)|пересечение множеств|
|множество1.difference(множество2)|уникальные в множестве1|
|frozenset(множество)|замораживает множество|


## Конструкции
| Конструкция | Описание |
|-|-|
|if условие: elif условие: else:|условие, иначе условие и иначе|
|while условие: else:|цикл пока выполняется условие, else если самостостоятельно закончил |
|break|прерывание|
|for i in массив(список значений)|подставляет в i поочереди значение |
|exp i for i in массив|подставляет в i поочереди значение и записывает значение|
|exp i for i in массив if условие|с условием |
|def имя_функции(аргументы)|функция(аругмент = значение по умолчанию;*args это неограниченное кол-во)|
|имя_функции = lambda аргументы: операция с аргументами для возврата | лямбда функция (сокращенная) где нет слова def, аргументы идут после lambda, операции после двоеточия|


## Работа с файлами
| Конструкция | Описание |
|-|-|
|a|открытие и добавление в файл (если нет, то создаст)|
|r|открытие для чтения|
|w|открытие для перезаписи в файл (если нет, то создаст)|
|w+|открытие для перезаписи в файл и чтения (если нет, то создаст)|
|r+|открытие для чтения и добавления в файл|
|-|-|
|open()|Открытие файла 1- имя файла, 2- режим, 3- кодировка (чтение происходит как запись в переменную)|
|.writelines(данные)|добавляет в файл строку с данными без разделителей|
|.close()|закрывает файл (если открыли, обязательно закрыть)|
|with open ('имя файла', 'режим') as переменная:  переменная.wtite(данные)|открытие файла как переменную, запись в переменную и закрытие файла|

## Модули
| Конструкция | Описание |
|-|-|
|модуль os|функции с операционной системой (import os - чтобы включить модуль)|
|os.chdir()|смена директории 1- новая директория|
|os.getcwd()|чтение директории|
|подмодуль os.path|вложенный модуль со своими функциями (import os.path)|
|os.path.basename|выводит базовый путь - на вход весь путь|
|os.path.abspath|выводит полный путь - на вход базовый путь|
|os|функции с операционной системой (import os)|
|моудль shutil|функции с действиями над файлами и папками(import shutil)|
|shutil.copyfile()|копирование содержимого из файла 1- в файл 2-|
|shutil.copy()|копирование содержимого из файла 1- в файл или папку 2-|
|shutil.rmtree()|удаляет дерикторию 1- |


