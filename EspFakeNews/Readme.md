# Детектор фейковых новостей на испанском языке

## Данные 

Правдивые новости парсились самостоятельно при помощи api сайтов и библиотеки requests: 
* Twitter 
* Facebook 
* Media: El Paise, El Mundo, RTVE

Ложные новости 
* База заказчика из 2500 новостей из тех же источников

## Технологии

* Метод опорных векторов (Tf-idf + Svm)
* Сверточные нейронные сети (CNN + word2vec)
* Рекуррентные нейронные сети (LSTM + word2vec)
* Bidirectional Encoder Representations from Transformers (BERT) 

