# Задания для Junior Data Scientist.

## 1. Разработать Веб-сервис emotion-detection с помощью multilabel classification на базе языковой модели BERT.
- Для создания REST API можно использовать что удобно, FastApi, Flask, Django и т. п..
- Модель и код запуска модели можно взять любую, готовую, например отсюда https://huggingface.co .
- Достаточно одного REST эндпоинта POST /emotion-detection на вход которого подаётся текст, на выходе получаем набор вероятностей классов (радость, грусть, злость и т. п.).
- Описать решение в README.md .
- Код запушить в GitHub и предоставить ссылку.
- Нужно будет объяснить, как работает сервис и выбранная модель.

## 2. Разработать Веб-сервис image-text-recognition на базе любого OCR фреймворка.
- Для создания REST API можно использовать что удобно, FastApi, Flask, Django и т. п..
- В качестве фреймворка можно использовать любой, например easyocr, mmocr, keras-ocr и тому подобные.
- Достаточно одного REST эндпоинта POST /text-recognition на вход которого подаётся картинка, на выходе получаем распознанный текст.
- Описать решение в README.md .
- Код запушить в GitHub и предоставить ссылку.
- Нужно будет объяснить, как работает сервис и выбранная модель.

## 3. Разработать Веб-сервис similar-texts-recognition с помощью выбранного алгоритма.
- Для создания REST API можно использовать что удобно, FastApi, Flask, Django и т. п..
- В качестве алгоритма матчинга использовать косинусное расстояние или любой алгоритм кластеризации и любой NLP фреймворк.
- Достаточно одного REST эндпоинта POST /similar-recognition на вход которого подаётся два текста, на выходе получаем метрику схожести двух текстов в пределах от 0 до 1.
- Описать решение в README.md .
- Код запушить в GitHub и предоставить ссылку.
- Нужно будет объяснить, как работает сервис и выбранный алгоритм.
