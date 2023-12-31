# ML Rec Sys

В рамках проекта вы поработаете с реальными сырыми данными от одного из крупнейших маркетплейсов страны.
Вас ждет интересная задача сопоставления и поиска наиболее похожих товаров.

Сопоставление или “мэтчинг” (англ. matching - соответствия) - одна из базовых задач машинного обучения, которая встречается в информационном поиске, компьютерном зрении, рекомендательных системах и др.

Вы познакомитесь с алгоритмами приближённого поиска ближайших соседей, научитесь создавать индексы в векторных базах данных и обучать ранжирующие модели. Эти навыки востребованы во многих сферах и позволят вам решать еще более интересные и сложные задачи.

## Используемые инструменты
* pandas
* numpy
* sklearn
* faiss

## Результаты
1) Мэтчинг для 100 000 обхектов : 140 секунд
2) Качество мэтчинга после ренджирования: 58,6%

## Цели
1) Проверить дополнительные индексы Faiss и достичь большей скорости и качества поиска
2) Проверить, улучшится ли качество поиска, если исходные данные кластеризировать, а после на каждый кластер обучить свой индекс.
3) Проверить, как можно улучщить качество ранжирования через дополнительные фичи
