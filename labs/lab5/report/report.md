---
## Front matter
title: "Компьютерный практикум по статистическому анализу данных"
subtitle: "Лабораторная работа № 5. Построение графиков"
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

Основная цель работы — освоить синтаксис языка Julia для построения графиков.

**Задачи**

1. Используя Jupyter Lab, повторите примеры.
2. Выполните задания для самостоятельной работы.

# Теоретическое введение

Julia — высокоуровневый свободный язык программирования с динамической типизацией, созданный для математических вычислений.[@julialang]. Эффективен также и для написания программ общего назначения. Синтаксис языка схож с синтаксисом других математических языков, однако имеет некоторые существенные отличия.

Для выполнения заданий была использована официальная документация Julia[@juliadoc].

# Выполнение лабораторной работы

Выполним примеры из лабораторной работы для изучения циклов и функций(рис. @fig:001 -  @fig:024)

![Примеры](image/1.png){#fig:001 width=70%}

![Примеры](image/2.png){#fig:002 width=70%}

![Примеры](image/3.png){#fig:003 width=70%}

![Примеры](image/4.png){#fig:004 width=70%}

![Примеры](image/5.png){#fig:005 width=70%}

![Примеры](image/6.png){#fig:006 width=70%}

![Примеры](image/7.png){#fig:007 width=70%}

![Примеры](image/8.png){#fig:008 width=70%}

![Примеры](image/9.png){#fig:009 width=70%}

![Примеры](image/10.png){#fig:010 width=70%}

![Примеры](image/11.png){#fig:011 width=70%}

![Примеры](image/12.png){#fig:012 width=70%}

![Примеры](image/13.png){#fig:013 width=70%}

![Примеры](image/14.png){#fig:014 width=70%}

![Примеры](image/15.png){#fig:015 width=70%}

![Примеры](image/16.png){#fig:016 width=70%}

![Примеры](image/17.png){#fig:017 width=70%}

![Примеры](image/18.png){#fig:018 width=70%}

![Примеры](image/19.png){#fig:019 width=70%}

![Примеры](image/20.png){#fig:020 width=70%}

![Примеры](image/21.png){#fig:021 width=70%}

![Примеры](image/22.png){#fig:022 width=70%}

![Примеры](image/23.png){#fig:023 width=70%}

![Примеры](image/24.png){#fig:024 width=70%}

Затем выполним задания(рис. @fig:008 - @fig:038)

![Задание 1](image/25.png){#fig:025 width=70%}

![Задание 1](image/26.png){#fig:026 width=70%}

![Задание 2 и 3](image/27.png){#fig:027 width=70%}

![Задание 4 и 5](image/28.png){#fig:028 width=70%}

![Задание 6, 7 и 8](image/29.png){#fig:029 width=70%}

![Задание 9](image/30.png){#fig:030 width=70%}

![Задание 10](image/31.png){#fig:031 width=70%}

![Задание 10](image/32.png){#fig:032 width=70%}

![Задание 10](image/33.png){#fig:033 width=70%}

![Задание 10](image/34.png){#fig:034 width=70%}

![Задание 11](image/35.png){#fig:035 width=70%}

![Задание 11](image/36.png){#fig:036 width=70%}

![Задание 11](image/37.png){#fig:037 width=70%}

![Задание 11](image/38.png){#fig:038 width=70%}


# Выводы

В результате выполнения работы освоили синтаксис языка Julia для построения графиков.

# Список литературы{.unnumbered}

::: {#refs}
:::


