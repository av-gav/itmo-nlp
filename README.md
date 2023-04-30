# itmo-nlp

Online course Natural Language Processing with Machine Learning

1. Выбираем задачу классификации, а конкретно - идентификации языка по фрагменту текста. Ограничимся языками, использующими кириллические алфавиты. Соответственно, нужно будет сформировать датасет с текстами на разных языках. Возможные источники для исходных текстов:
- Wikipedia (https://en.wikipedia.org) // можно попробовать датасеты из Tensorflow
- Tatoeba (https://attoeba.org) // данные можно получать с помощью https://pypi.org/project/tatoebatools/
- UDHR in Unicode (https://unicode.org/udhr) // есть модуль в NLTK, но можно и прямо с сайта (plaintext)
- CC-100: Monolingual Datasets from Web Crawl Data (https://data.statmt.org/cc-100)
- Коллекции текстов на малых языках (http://web-corpora.net/wsgi3/minorlangs/download)

2. Для базовой модели векторизацию проводим с помощью CountVectorizer, классификатор - Logistic Regression. Векторизация по символам, используем 1- и 2-граммы.

3. В качестве более продвинутого варианта векторизацию попробуем сделать с помощью TF-IDF, и для классификации - Bayes.

4. И еще как один из вариантов базовых моделей можно попробовать MLP.

5. В качестве идей для улучшенных моделей на следующее задание - RNN/LSTM. 
