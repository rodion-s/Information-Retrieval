https://www.kaggle.com/c/text-relevance-competition-ir-1-ts-spring-2020/overview

##### Ник в соревновании: Rodion Sulzhenko

### Описание решения:
1) Документы лемматизированы (pymorphy), убраны стоп-слова (nltk.stopwords)
2) Опечатки в запросах исправлены с помощью YandexSpeller API
3) Ранжирование с помощью BM-25 для заголовока + текста документа



### Инструкция по запуску:
1) Распаковать в данную папку архив text-relevance-competition-ir-1-ts-spring-2020
2) Запустить все ячейки ноутбука Parsing
3) Запустить все ячейки ноутбука TextRelevance
