# NLP_lab2
В лабораторной работе №2 необходимо сделать следующее:
1. Предобработать собранный корпус (датасет новостей): удаление знаков препинания и лишних символов, токенизация, приведение к нормальной форме, удаление стоп-слов. Полезные библиотеки: <br>
SpaCy: https://spacy.io Очень много функций, однако большинство из них реализовано только для английского языка <br>
Natural Language Toolkit (NLTK): https://www.nltk.org Много поддерживаемых языков, широкий набор инструментов и решаемых задач, однако многие реализованные в этой библиотеке алгоритмы довольно простые, из-за чего точность будет далека от оптимальной <br>
Морфологический анализатор pymorphy2 для русского языка: https://pymorphy2.readthedocs.io в частности, поддерживает приведение слов к нормальной форме
Yandex Mystem 3.1: https://github.com/nlpub/pymystem3 <br>
2. Векторизовать тексты (CountVectorizer и/или TfIdfVectorizer)  <br>
С помощью моделей классического машинного обучения выполнить классификацию категорий собственного новостного корпуса. Добиться как можно лучшего качества. Использовать минимум 6 методов (моделей) <br>
3. Выполнить анализ полученных результатов. Сравнить метрики качества, добавить необходимые визуализации, сделать выводы.
