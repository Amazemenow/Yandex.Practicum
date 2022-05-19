**Описание на русском ниже**

# Determination of a prospective tariff for telecom company

## Data:
---
Dataframe calls:
 - id — unique call number
 - call_date — call date
 - duration — call duration in minutes
 - user_id — id of the user who made the call

 Dataframe internet:
 - id — unique session number
 - mb_used — the amount of Internet traffic spent per session (in megabytes)
 - session_date — internet session date
 - user_id — user ID

 Dataframe messages:
 - id — unique message number
 - message_date — message date
 - user_id — ID of the user who sent the message

 Dataframe tariffs:
 - tariff_name — tariff name
 - rub_monthly_fee — monthly subscription fee in rubles
 - minutes_included — the number of minutes of conversation per month included in the subscription fee
 - messages_included — number of messages per month included in the subscription fee
 - mb_per_month_included — the amount of Internet traffic included in the subscription fee (in megabytes)
 - rub_per_minute — the cost of a minute of conversation in excess of the tariff package (for example, if the tariff includes 100 minutes of conversation per month, then a fee will be charged from 101 minutes)
 - rub_per_message — the cost of sending a message in excess of the tariff package

 Dataframe users:
 - user_id — unique user ID
 - first_name — username
 - last_name — user last name
 - age — user age (years)
 - reg_date — tariff activation date (day, month, year)
 - churn_date — date of termination of using the tariff (if the value is omitted, then the tariff was still valid at the time of uploading the data)
 - city — user's city of residence
 - tariff — tariff plan name

## Goal:
---
Make a preliminary analysis of tariffs on a small sample of customers (500 users) and determine who they are, what tariff they use, how many calls and messages each sent in 2018. It is necessary to analyze the behavior of customers and draw a conclusion - which tariff is better for the company from the point of investment of the marketing budget.


## Libraries used:
*pandas*
<br>*numpy*
<br>*matplotlib*
<br>*scipy*


_______________________________________________________________________________
# Определение перспективного тарифа для телеком-компании

## Данные:
---
Таблица calls содержит информацию о звонках:
 - id — уникальный номер звонка
 - call_date — дата звонка
 - duration — длительность звонка в минутах
 - user_id — идентификатор пользователя, сделавшего звонок

 Таблица internet содержит информацию об интернет-сессиях:
 - id — уникальный номер сессии
 - mb_used — объём потраченного за сессию интернет-трафика (в мегабайтах)
 - session_date — дата интернет-сессии
 - user_id — идентификатор пользователя

 Таблица messages содержит информацию о сообщениях:
 - id — уникальный номер сообщения
 - message_date — дата сообщения
 - user_id — идентификатор пользователя, отправившего сообщение

 Таблица tariffs содержит информацию о тарифах:
 - tariff_name — название тарифа
 - rub_monthly_fee — ежемесячная абонентская плата в рублях
 - minutes_included — количество минут разговора в месяц, включённых в абонентскую плату
 - messages_included — количество сообщений в месяц, включённых в абонентскую плату
 - mb_per_month_included — объём интернет-трафика, включённого в абонентскую плату (в мегабайтах)
 - rub_per_minute — стоимость минуты разговора сверх тарифного пакета (например, если в тарифе 100 минут разговора в месяц, то со 101 минуты будет взиматься плата)
 - rub_per_message — стоимость отправки сообщения сверх тарифного пакета

 Таблица users содержит информацию о пользователях):
 - user_id — уникальный идентификатор пользователя
 - first_name — имя пользователя
 - last_name — фамилия пользователя
 - age — возраст пользователя (годы)
 - reg_date — дата подключения тарифа (день, месяц, год)
 - churn_date — дата прекращения пользования тарифом (если значение пропущено, то тариф ещё действовал на момент выгрузки данных)
 - city — город проживания пользователя
 - tariff — название тарифного плана

## Задача:
---
сделать предварительный анализ тарифов на небольшой выборке клиентов (500 пользователей) и определить кто они, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год. Нужно проанализировать поведение клиентов и сделать вывод — какой тариф лучше для компании с точки инвестиций маркетингового бюджета.


## Используемые библиотеки:
*pandas*
<br>*numpy*
<br>*matplotlib*
<br>*scipy*



     