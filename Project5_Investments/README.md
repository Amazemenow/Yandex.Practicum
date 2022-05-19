**Описание на русском ниже**

# Airlines analytics

## Data:
---
<br>Dataframe airports:
 - airport_code — three-letter airport code,
 - airport_name — airport name,
 - city — city name,
 - timezone — timezone.
 
<br>Dataframe aircrafts:
 - aircraft_code — aircraft model code,
 - model — airplane model,
 - range — flight range.
 
<br>Dataframe tickets:
 - ticket_no — unique ticket number,
 - passenger_id — unique passenger ID,
 - passenger_name — name and surname of the passenger.
 
<br>Dataframe flights:
 - flight_id — unique flight identifier,
 - departure_airport — departure airport,
 - departure_time — date and time of departure,
 - arrival_airport — arrival airport,
 - arrival_time — date and time of arrival,
 - aircraft_code — aircraft unique identifier.
 
<br>Dataframe ticket_flights:
 - ticket_no — ticket number,
 - flight_id — unique flight identifier.
 
<br>Dataframe festivals:
 - festival_id — unique number of the festival,
 - festival_date — date of the festival,
 - festival_city — city of the festival,
 - festival_name — festival name.

## Goal:
---
study the database and analyze the demand of passengers for flights to cities where the largest festivals are held.


## Libraries used:
*pandas*
<br>*numpy*
<br>*matplotlib*
<br>*seaborn*
<br>*requests*
<br>*BeautifulSoup*


_______________________________________________________________________________
# Аналитика в авиакомпании

## Данные:
<br>Таблица airports — информация об аэропортах:
 - airport_code — трёхбуквенный код аэропорта,
 - airport_name — название аэропорта,
 - city — город,
 - timezone — часовой пояс.
 
<br>Таблица aircrafts — информация о самолётах:
 - aircraft_code — код модели самолёта,
 - model — модель самолёта,
 - range — дальность полётов.
 
<br>Таблица tickets — информация о билетах:
 - ticket_no — уникальный номер билета,
 - passenger_id — уникальный идентификатор пассажира,
 - passenger_name — имя и фамилия пассажира.
 
<br>Таблица flights — информация о рейсах:
 - flight_id — уникальный идентификатор рейса,
 - departure_airport — аэропорт вылета,
 - departure_time — дата и время вылета,
 - arrival_airport — аэропорт прилёта,
 - arrival_time — дата и время прилёта,
 - aircraft_code — уникальный идентификатор самолёта.
 
<br>Таблица ticket_flights — стыковая таблица «рейсы-билеты»:
 - ticket_no — номер билета,
 - flight_id — уникальный идентификатор рейса.
 
<br>Таблица festivals — информация о фестивалях:
 - festival_id — уникальный номер фестиваля,
 - festival_date — дата проведения фестиваля,
 - festival_city — город проведения фестиваля,
 - festival_name — название фестиваля.

## Задача:
---
изучить базу данных и проанализировать спрос пассажиров на рейсы в города, где проходят крупнейшие фестивали.


## Используемые библиотеки:
*pandas*
<br>*numpy*
<br>*matplotlib*
<br>*seaborn*
<br>*requests*
<br>*BeautifulSoup*



     