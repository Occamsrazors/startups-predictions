# Предсказание успешности стартапа

**Цель и задачи:** разработать модель для предсказания успешности стартапа (закроется или нет).
**Описание данных**
Датасет состоит из двух файлов: тренировочный набор (около 53к записей) и тестовый набор (около 13к записей). Тренировочный набор содержит целевой признак `status`, указывающий на то, закрылся стартап или продолжает действовать. Временной период - `'1970-01-01'` по `'2018-01-01'`. Дата формирования выгрузки - `'2018-01-01'`.

- `kaggle_startups_train_01.csv` - информация (53 000) стартапах, которые будут использоваться в качестве обучающих данных.
- `kaggle_startups_test_01.csv` - информация (13 000) стартапах, которые будут использоваться в качестве тестовых данных. Ваша задача - предсказать значение 'status' для каждого стартапа из этого датасета.
- `name` - идентификатор (название) стартапа в тестовом наборе.
- `status` - целевой признак. Для каждого стартапа предскажите категориальное значение соответствующее прогнозу `['operating', 'closed']`.
