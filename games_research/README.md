# Поиск закономерностей в данных о продажах игр
___

## Описание проекта

В проекте проведен анализ игровых рынков Северной Америки, Европы и Японии за 2014-2016 гг. Составлены портреты пользователей разных стран и выявлены важные закономерности, влияющие на продажи игр. Сформулированы и проверены гипотезы относительно поведения пользователей при помощи t-тестов. Результат был достигнут при использовании модуля stats из библиотеки scipy. Изучена взаимосвязь данных, найдены коэффициенты корреляции Пирсона с помощью метода corr. Освоены основные типы визуализации данных: plot, barplot, boxplot, scatterplot. Автоматизировано построение графиков, использована утилита subplots для комбинированного отображения графиков
___
## Материалы

[Презентация с результатами исследования](https://drive.google.com/file/d/1f36-E_4rTFzUzM0ikpTDxc9e_L7Vi9uk/view?usp=sharing)
___

## Используемые библиотеки

  *seaborn, matplotlib, pandas, scipy, pylab*
  ___

## Задача

Интернет-магазин продает по всему миру компьютерные игры.Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation).Необходимо выявить определяющие успешность игры закономерности.

В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр.
___
## Описание данных

Наименование  |  Описание
--|--
Name   |  название игры
Platform | платформа
Year_of_Release   |  год выпуска
Genre   |  жанр игры
  NA_sales |  продажи в Северной Америке (миллионы проданных копий)
  EU_sales | продажи в Европе (миллионы проданных копий)
JP_sales   |  продажи в Японии (миллионы проданных копий)
Other_sales   |  продажи в других странах (миллионы проданных копий)
  Critic_Score |  оценка критиков (максимум 100)
  User_Score |  оценка пользователей (максимум 10)
Rating   |  рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию
___