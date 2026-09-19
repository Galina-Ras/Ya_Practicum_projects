# Портфолио аналитика данных — Галина Рассказова

Проекты курса «Аналитик данных» Яндекс Практикума. Тетрадки подготовлены для GitHub: пути к данным локальные, служебные комментарии ревьюера убраны, тяжёлые выводы карт/Plotly сокращены, чтобы репозиторий можно было клонировать и запускать.

**Контакты:** [yabooger@yandex.ru](mailto:yabooger@yandex.ru) · Telegram [@GalyaRas](https://t.me/GalyaRas) · Москва

Резюме: [`resume/Rasskazova_Galina.pdf`](resume/Rasskazova_Galina.pdf)

## Стек

Python (pandas, NumPy, matplotlib, seaborn, Plotly, SciPy, scikit-learn), SQL, Tableau, Jupyter, статистические тесты, A/B, когортный анализ, RFM, базовый ML.

## Проекты

| # | Проект | Что сделано | Папка |
|---|--------|-------------|-------|
| 1 | [Рынок общепита Москвы](01-moscow-cafes) | EDA, карты, рекомендация по открытию кофейни | `01-moscow-cafes` |
| 2 | [TED Talks](02-ted-talks) | Дашборд Tableau: история, темы, авторы | `02-ted-talks` |
| 3 | [NPS телекома](03-nps-telecom) | SQL-витрина + дашборд NPS | `03-nps-telecom` |
| 4 | [Procrastinate Pro+](04-procrastinate) | LTV, CAC, ROI, удержание, каналы | `04-procrastinate` |
| 5 | [GoFast](05-gofast-scooters) | Статистика, выручка, проверка гипотез | `05-gofast-scooters` |
| 6 | [A/B-тест интернет-магазина](06-ab-test) | ICE/RICE и анализ A/B | `06-ab-test` |
| 7 | [Отток фитнес-клуба](07-gym-churn) | Логрег vs случайный лес, кластеры | `07-gym-churn` |
| 8 | [Стримчик](08-games-streamchik) | Рынок игр, портреты регионов, гипотезы | `08-games-streamchik` |
| 9 | [E-commerce](09-ecommerce) | Ассортимент, RFM, кластеризация | `09-ecommerce` |

## Как запустить

```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

Откройте тетрадку в папке проекта. CSV лежат в `data/` рядом с `.ipynb`.

Исходники курса **не изменялись**. Что именно сделано в копиях — в [`CHANGES.md`](CHANGES.md).
