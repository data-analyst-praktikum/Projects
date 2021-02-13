# Оптимизизация маркетинговых затрат согласно данным от Яндекс.Афиши/Marketing costs optimization according to Yandex.Afisha data

## Введение/Introduction

Оптимизизация маркетинговых затрат согласно следующим данным от Яндекс.Афиши с июня 2017 по конец мая 2018 года:
- лог сервера с данными о посещениях сайта Яндекс.Афиши;
- выгрузка всех заказов за этот период;
- статистика рекламных расходов.

Мы изучим:
- как люди пользуются продуктом;
- когда они начинают покупать;
- сколько денег приносит каждый клиент;
- когда клиент окупается.

Marketing costs optimization according to following data from Yandex.Afisha during june 2017 to the end of may 2019:
- server log data about Yandex.Afisha visits;
- all orders retrieved for this period;
- marketing costs statistics.

We'll study:
- how people start to use product;
- when do they start to buy;
- how big is revenue from each client;
- when do clients return on marketing investments.

## Описание шагов/Steps description
- Предварительная обработка данных: преобразование форматов столбцов, замена названий, поиск дубликатов.

  Preprocessing data: column format conversion, change of headlines, duplicates search.
  
- Расчёт продуктовых метрик: количество посетителей в день DAU (daily active users), неделю WAU (weekly active users), месяц MAU (monthly active users), средняя частота посещений, продолжительность типичной пользовательской сессии, коэффициента удержания (Retention Rate).

  Product metrics calculation: visitors number per day DAU (daily active users), per week WAU (weekly active users), per month MAU (monthly active users), average visits frequency, average session length, retention rate.
  
- Расчёт метрик электронной коммерции: среднее время с момента первого посещения сайта до совершения покупки, среднее количество покупок на одного покупателя за период, средний чек, LTV (lifetime value).

  eCommerce metrics calculation: average time from the first visiting to the first order, average orders number per user for the period, average revenue, LTV (lifetime value).
  
- Расчёт маркетинговых метрик: общая сумма расходов на маркетинг и по источникам, средний CAC (customer acquisition cost) на одного покупателя для всего проекта и для каждого источника трафика, ROMI (return on marketing investments) по когортам в разрезе источников.

  Marketing metrics calculation: summary marketing costs and per sources, average CAC (customer acquisition cost) per user for the whole project and for each traffic source, ROMI (return on marketing investments) per cohorts in the context of sources.
  
- Выводы и рекомендации: сравнение рекламных источников, выводы о маркетинговых, продуктовых и метрик электронной коммерции, определение самых перспективных когорт клиентов.

  Conclusions and recommendations: marketing sources comparison, conclusions about product, marketing and eCommerce metrics, determination of the most promising client cohorts.

## Используемые инструменты/Features covered
- Преобразование данных при помощи библиотеки `Pandas`.
  
  Data conversion by the use of `Pandas` library.
  
- Агрегирование данных при помощи `groupby()` и `pivot_table'.
  
  Data aggregation by the use of `groupby()` and `pivot_table`.
  
- Визуализация данных: графики, гистограммы, круговые диаграммы, тепловые карты при помощи библиотек `Matplotlib` и `seaborn`.
  
  Data visualization: plotting, histograms, pie charts, heatmaps by the use of `Matplotlib` and `seaborn` libraries.
  
- Выполнение математических расчётов при помощие библиотеки `NumPy`.
  
  Mathematic computing by the use of `NumPy` library.
  
- Создание функций.
  
  Creation of functions.
