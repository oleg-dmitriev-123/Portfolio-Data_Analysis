# Исследование объявлений о продаже квартир
___

## Описание проекта
___
Выявлена зависимость стоимости квадратного метра жилья от важнейших параметров. Отслежена динамика цен на недвижимость за 2014-2019 гг. В проекте упор сделан на исследовательский анализ данных. Изучены распределения данных и их основные характеристики. Произведена обработка пропусков с использованием группировки по значениям датафрейма. Выполнена очистка данных от выбросов с помощью рассчета межквартильных размахов на диаграмме boxplot. 

## Используемые библиотеки
  ___
*pandas, matplotlib*

## Задача
___
В проекте представлены данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Необходимо определить рыночную стоимость объектов недвижимости путем установления ключевых параметров - это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

## Описание данных
___
Наименование  |  Описание
--|--
airports_nearest   |  расстояние до ближайшего аэропорта в метрах (м)
balcony   |  число балконов
ceiling_height   |  высота потолков (м)
cityCenters_nearest |  расстояние до центра города (м)
days_exposition   |  сколько дней было размещено объявление (от публикации до снятия)
first_day_exposition   |  дата публикации
floor   |  этаж
floors_total   | всего этажей в доме
is_apartment   | апартаменты (булев тип)
kitchen_area   | площадь кухни в квадратных метрах (м²)
last_price   | цена на момент снятия с публикации
living_area   | жилая площадь в квадратных метрах (м²)
locality_name   | название населённого пункта
open_plan   |  свободная планировка (булев тип)
parks_around3000   |  число парков в радиусе 3 км
parks_nearest   |  расстояние до ближайшего парка (м)
ponds_around3000   |  число водоёмов в радиусе 3 км
ponds_nearest   |  расстояние до ближайшего водоёма (м)
rooms   |  число комнат
studio  | квартира-студия (булев тип)
total_area   | площадь квартиры в квадратных метрах (м²)
total_images  | число фотографий квартиры в объявлении
