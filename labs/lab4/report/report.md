---
## Front matter
title: "Компьютерный практикум по статистическому анализу данных"
subtitle: "Лабораторная работа № 4. Линейная алгебра"
author: "Демидова Екатерина Алексеевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: false # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Введение

**Цель работы**

Основной целью работы является изучение возможностей специализированных пакетов Julia для выполнения и оценки эффективности операций над объектами линейной алгебры.

**Задачи**

1. Используя Jupyter Lab, повторите примеры.
2. Выполните задания для самостоятельной работы.

# Теоретическое введение

Julia — высокоуровневый свободный язык программирования с динамической типизацией, созданный для математических вычислений.[@julialang]. Эффективен также и для написания программ общего назначения. Синтаксис языка схож с синтаксисом других математических языков, однако имеет некоторые существенные отличия.

Для выполнения заданий была использована официальная документация Julia[@juliadoc].

# Выполнение лабораторной работы

Выполним примеры из лабораторной работы для изучения циклов и функций(рис. @fig:001 -  @fig:007)

![Поэлементные операции над многомерными массивами](image/1.png){#fig:001 width=70%}

![Примеры. Транспонирование, след, ранг, определитель и инверсия матрицы](image/2.png){#fig:002 width=70%}

![Примеры. Вычисление нормы векторов и матриц, повороты, вращения](image/3.png){#fig:003 width=70%}

![Примеры. Матричное умножение, единичная матрица, скалярное произведение](image/4.png){#fig:004 width=70%}

![Примеры. Факторизация. Специальные матричные структуры](image/5.png){#fig:005 width=70%}

![Примеры. Факторизация. Специальные матричные структуры](image/6.png){#fig:006 width=70%}

![Примеры. Общая линейная алгебра](image/7.png){#fig:007 width=70%}

Затем выполним задания(рис. @fig:008 - @fig:014)

![Задание 1, 2](image/8.png){#fig:008 width=70%}

![Задание 2](image/9.png){#fig:009 width=70%}

![Задание 3](image/10.png){#fig:010 width=70%}

![Задания 3](image/11.png){#fig:011 width=70%}

![Задание 3](image/12.png){#fig:012 width=70%}

![Задания 4](image/13.png){#fig:013 width=70%}

![Задание 4](image/14.png){#fig:014 width=70%}


# Выводы

В результате выполнения работы освоили применение циклов функций и сторонних для Julia пакетов для решения задач линейной алгебры и работы с матрицами.

# Список литературы{.unnumbered}

::: {#refs}
:::


