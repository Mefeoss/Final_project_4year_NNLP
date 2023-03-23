# Проект: детоксификация русского текста

## Авторы: Феоктистова Эмма, Щурова Елизавета

#### Ссылка на соревнование: https://github.com/s-nlp/russe_detox_2022

#### Основной код: sentence style transfer.ipynb

#### На данный момент:
1) у Delete решения

Фильтруются плохие слова из предложений по заранее приготовленному словарю

2) у T5 решения

Обучается сетка из hugging face

__Веса__:  в папках t5_base_train_300, t5_base_train_1000, t5_base_train_3000, t5_base_train_10000

3) RuPrompt

Из библиотеки RuPrompt, которая позволяет решить проблему дообучивания больших nlp сеток, сами сетки не трогая  (https://habr.com/ru/company/sberdevices/blog/596103/)

__Веса__: в папках checkpoint-600 и checkpoint-550

### Что можно еще попробовать?

- замерить метрики у более ранних весов T5
- поиграться с гиперпараметрами T5
- попробовать https://github.com/s-nlp/rudetoxifier 
- попробовать какую-нибудь ещё архитектуру из https://huggingface.co/docs/transformers/index
