# Портфолио аналитика данных

**Галина Рассказова** · Москва  
[GitHub](https://github.com/Galina-Ras) · [Telegram](https://t.me/GalyaRas) · [yabooger@yandex.ru](mailto:yabooger@yandex.ru)  
Резюме: [PDF](resume/Rasskazova_Galina.pdf)

Проекты курса «Аналитик данных» Яндекс Практикума: от предобработки и EDA до SQL, Tableau, A/B-тестов и базового ML.

## Стек

`Python` `pandas` `NumPy` `matplotlib` `seaborn` `Plotly` `SciPy` `scikit-learn`  
`SQL` `Tableau` `Jupyter` `A/B-тесты` `когортный анализ` `RFM`

## Проекты

| | Проект | Задача | Результат |
|---|--------|--------|-----------|
| 01 | [Рынок общепита Москвы](01-moscow-cafes) | Куда открыть кофейню | Рекомендация по округу, формату и цене чашки |
| 02 | [TED Talks](02-ted-talks) | История конференций | [Дашборд Tableau](https://public.tableau.com/views/TEDTalksTableauproject/sheet22?:language=en-US&:display_count=n&:origin=viz_share_link) |
| 03 | [NPS телекома](03-nps-telecom) | Лояльность клиентов | SQL-витрина + [дашборд NPS](https://public.tableau.com/views/2__17279900065660/sheet17?:language=en-US&:display_count=n&:origin=viz_share_link) |
| 04 | [Procrastinate Pro+](04-procrastinate) | Реклама не окупается | Разбор LTV / CAC / ROI по странам и каналам |
| 05 | [GoFast](05-gofast-scooters) | Самокаты и подписки | Проверка гипотез, оценка акций |
| 06 | [A/B-тест магазина](06-ab-test) | Рост выручки | ICE/RICE + решение по тесту |
| 07 | [Отток фитнес-клуба](07-gym-churn) | Кто уйдёт в следующем месяце | Логрег vs случайный лес, 5 кластеров |
| 08 | [Стримчик](08-games-streamchik) | Игры на 2017 год | Портреты NA / EU / JP, жанры и платформы |
| 09 | [E-commerce](09-ecommerce) | Профили покупателей | RFM-сегменты для рассылок |

Каждая папка: тетрадка, `data/`, короткий README с выводами.

## Как запустить

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Откройте `.ipynb` в папке проекта. CSV лежат в `data/` рядом с тетрадкой.

Что изменено относительно исходников Практикума — в [CHANGES.md](CHANGES.md).
