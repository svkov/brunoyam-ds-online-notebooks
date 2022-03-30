# Курс по Machine Learning школы "Бруноям"

Группа SC341-2558

# Содержание

# Содержание

1. Введение в Python - базовые операции питона, синтаксис циклов, if-ов, функций и прочего
2. Numpy и Pandas начало - Индексация по массивам numpy, первое знакомство с pandas
3. Pandas продолжение, matplotlib\seaborn - Погружение в pandas, обработка, агрегация и фильтрация данных; Визуализация данных
4. Базы данных - Синтаксис SQL, работа с БД из питона, связь pandas и БД
5. Математика 1 - Задачи по оптимизации и теории вероятности
6. Математика 2 - Проверка гипотез, доверительные интервалы, центральная предельная теорема
7. Машинное обучение 1 - Линейная и логистичесая регрессия, метрики качества обучения, работаем с датасетом Boston Housing Prices и MNIST (рукописные цифры)
8. Машинное обучение 2 - Способы предобработки и нормализации данных; дерево решений; валидация моделей
9. Машинное обучение 3 - Ансамбли моделей: Беггинг, Случайный лес, бустинг, стекинг
10. Машинное обучение 4 - kNN, SVM, наивный байесовский классификатор
11. Обучение без учителя - Алгоритмы KMeans, DBSCAN, агломеративная кластеризация, работаем с датасетом о вине, понижаем размерность при помощи метода главных компонент (PCA)
12. Временные ряды - Проверка на стационарность, модель ARIMA, приведение ряда к стационарному виду, кросс-валидация временных рядов, использование преобразования Фурье для прогнозирования временных рядов (датасет с погодой)
13. Нейронные сети - Перцептрон, функции активации, обратное распростронение ошибки, работа с датасетами MNIST и Fashion MNIST
14. Нейронные сети: CV - Сверточные нейронные сети, продолжаем работать с MNIST, выбираем лучшую модель
15. Нейронные сети: NLP - Методы предобработки текста, методы векторизации текста
16. Нейронные сети: NLP - Знакомство с SOTA моделями
17. Хорошие практики Data Science
18. Теория воспроизводимых вычислений; знакомство со snakeMake

# Структура репозитория

- `data/` - папка с данными, которые будем использовать в классе
- `images/` - папка с картинками, которые будут использоваться в ноутбуках
- `notebooks/` - папка с ноутбуками, по которым проходят занятия
- `environment.yml` - список зависимостей проекта

# Требования по оформлению ДЗ

Домашние задания оформляются в виде jupyter ноутбуков, которые публикуются в github-репозиторий.

Ноутбуки должны быть названы в соответствии с номером домашней работы.

Хорошее название - `01-homework.ipynb`

Плохое название - `python basics homework.ipynb`, `first homework.ipynb`

Также в ноутбуки можно выкладывать решение задачек из класса, которые не успеваем разобрать, это всегда плюс.


## Почему именно такие названия?

Во-первых, так гораздо проще проверять задания и отслеживать досдачу старых домашек. 01 = первая домашка, 06 = шестая домашка. 

Названия файлов сортируются по алфавиту, поэтому важно, чтобы цифры были в самом начале.

Вместо пробелов лучше использовать тире `-` или нижние подчеркивания `_`.

Если ноутбук будет назван темой домашки или буквами будут написаны числа, то на поиск нужной домашки уйдет какое-то время.

Во-вторых, вам самим будет проще потом искать код из старых ноутбуков, если он понадобится в будущем.

В-третьих, репозиторий просто будет выглядеть красиво, если все ноутбуки будут называться в одном стиле. В красивом репозитории проще разобраться.


## Требования к репозиторию

Все ноутбуки с домашками должны находиться в одном месте. Например, в корне проекта, либо в отдельной папке notebooks.

В репозитории должен быть файл  `.gitignore`, в который следует помещать все файлы, которые не относятся к решению, например папки `.ipynb_checkpoints`, `__pycache__` и другие. 

Также желательно не хранить данные в репозитории. Вместо этого лучше оставить ссылку на данные, если эти данные не были даны в условии задачи.

## Требования к оформлению ноутбуков

Каждый уровень задач (Easy, Normal и Hard) разделяйте текстовой ячейкой, в которой пишите название задачи и ее условие. Например, так:

```
# Easy

Нужно написать функцию, которая на вход получает список из чисел, а на выходе дает список, где каждое число возведено в квадрат. Решать при помощи цикла.
```

Решетка превратит строку в заголовок при запуске (убедитесь, что ячейка типа Markdown).

После заголовка можно писать код, который относится к данному заданию.

Желательно комментировать результаты, получающиеся в задаче.

Код по каждой задаче должен быть разнесен в разные ячейки. 

Комментарии в коде должны быть по коду. Если есть потребность прокомментировать результат или какое-то решение, то лучше это сделать в текстовой ячейке.