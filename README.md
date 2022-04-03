# MovieLens - сравнение подходов к построению рекомендаций

`movielens_recommender.ipynb` - код и текстовые комментарии
`data` - данные, использованные в работе

### Постановка задачи

В работе было проведено сравнение двух подходов к построению рекомендаций: 

- коллаборативный: модель со скрытыми признаками и ALS оптимизаций
- коллаборативный + контетный: LightFM из библиотеки `lightfm`

Данные: [MovieLens](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset?datasetId=339&searchQuery=lightfm)

### Информационные ресурсы, использованные при подготовке

1. [Метрики качества ранжирования (habr.com)](https://habr.com/ru/company/econtenta/blog/303458/)
2. [Рекомендательные системы: проблемы и методы решения. Часть 1 (habr.com)](https://habr.com/ru/company/prequel/blog/567648/)
3. [How I would explain building “LightFM Hybrid Recommenders” to a 5-year old! (towardsdatascience.com)](https://towardsdatascience.com/how-i-would-explain-building-lightfm-hybrid-recommenders-to-a-5-year-old-b6ee18571309)
