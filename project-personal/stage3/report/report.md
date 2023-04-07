---
## Front matter
title: "Индивидуальный проект. Третий этап"
author: "Чемоданова А.А."

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

# Цель работы

Добавить к сайту данные о себе.

# Задание

Список добавляемых данных:
Список достижений.
Добавить информацию о навыках (Skills).
Добавить информацию об опыте (Experience).
Добавить информацию о достижениях (Accomplishments).
Сделать пост по прошедшей неделе.
Добавить пост на тему: Язык разметки Markdown.


# Теоретическое введение

Hugo - это генератор статичных сайтов, популярность которого быстро растет. Основанный на языке Go, Hugo создает сайт значительно быстрее, чем большинство других генераторов статических сайтов, включая Jekyll.

Мы продолжаем оформлять свой сайт.

# Выполнение лабораторной работы

Для начала добавим информацию о своих навыках. (рис. @fig:001).

![Измененная информация о навыках](image/1.png){#fig:001 width=70%}

Теперь изменим информацию о опыте.  (рис. @fig:002).

![Измененная информация об опыте](image/2.png){#fig:002 width=70%}

И добавим информацию о достижениях.  (рис. @fig:003).

![Измененная информация о достижениях](image/3.png){#fig:003 width=70%}

Добавим пост на тему: Язык разметки Markdown.  (рис. @fig:004).

![Пост на тему: Язык разметки Markdown.](image/4.png){#fig:004 width=70%}

Добавим пост по прошедшей неделе.  (рис. @fig:005).

![Пост по прошедшей неделе](image/5.png){#fig:005 width=70%}

Измененный сайт. (рис. @fig:006).

![Измененный сайт](image/6.png){#fig:006 width=70%}


# Выводы

Мы добавили к сайту данные о себе.
