# NPS телекоммуникационной компании

Оценка потребительской лояльности клиентов из России: SQL-витрина и дашборд Tableau.

## Дашборд

https://public.tableau.com/views/2__17279900065660/sheet17?:language=en-US&:display_count=n&:origin=viz_share_link

Локальная копия: `nps_dashboard.twbx`

## Что в тетрадке

- Подключение к SQLite (схема Практикума: user, location, сегменты).
- SQL: витрина с NPS-группами (сторонник / нейтрал / критик), городом, ОС, lifetime.
- Правки названий городов и подписей сегментов.
- Выгрузка CSV для Tableau.

Исходная база `telecomm_csi.db` и выгрузка ~63 МБ в git не входят. Если положить `.db` или `telecomm_csi_tableau.csv` в `data/`, тетрадка прочитает их сама.

## Запуск

```bash
jupyter notebook nps_sql.ipynb
```
