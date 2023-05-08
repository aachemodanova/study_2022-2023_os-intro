---
## Front matter
title: "Индивидуальный проект. Шестой этап"
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

Добавить к сайту данные и два поста. Размещение двуязычного сайта на Github.
 
# Задание


Сделать поддержку английского и русского языков.
Разместить элементы сайта на обоих языках.
Разместить контент на обоих языках.
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору (на двух языках).




# Теоретическое введение

Hugo - это генератор статичных сайтов, популярность которого быстро растет. Основанный на языке Go, Hugo создает сайт значительно быстрее, чем большинство других генераторов статических сайтов, включая Jekyll.

Мы продолжаем оформлять свой сайт.

# Выполнение лабораторной работы


Сделать поддержку английского и русского языков.(рис. @fig:001).

![Языки](image/1.png){#fig:001 width=70%}


Разместить элементы сайта на обоих языках.

Русский. (рис. @fig:002).

![Русский](image/2.png){#fig:002 width=70%}

Английский.  (рис. @fig:003).

![Английский](image/3.png){#fig:003 width=70%}


Разместить контент на обоих языках.

Русский. (рис. @fig:004).

![Русский](image/4.png){#fig:004 width=70%}

Английский.  (рис. @fig:005).

![Английский](image/5.png){#fig:005 width=70%}


Сделать пост по прошедшей неделе. (рис. @fig:006).

![Недельный пост](image/6.png){#fig:006 width=70%}


Добавить пост на тему по выбору (на двух языках).(рис. @fig:007).

![Пост на тему по выбору](image/7.png){#fig:007 width=70%}



# Выводы

Добавили к сайту данные и два поста.
