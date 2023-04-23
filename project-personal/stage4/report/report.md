---
## Front matter
title: "Индивидуальный проект. Четвертый этап"
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

Добавить к сайту данные о себе и два поста.

# Задание

Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
        eLibrary : https://elibrary.ru/;
        Google Scholar : https://scholar.google.com/;
        ORCID : https://orcid.org/;
        Mendeley : https://www.mendeley.com/;
        ResearchGate : https://www.researchgate.net/;
        Academia.edu : https://www.academia.edu/;
        arXiv : https://arxiv.org/;
        github : https://github.com/.
Сделать пост по прошедшей неделе.
Добавить пост на тему по выбору:
        Оформление отчёта.
        Создание презентаций.
        Работа с библиографией.


# Теоретическое введение

Hugo - это генератор статичных сайтов, популярность которого быстро растет. Основанный на языке Go, Hugo создает сайт значительно быстрее, чем большинство других генераторов статических сайтов, включая Jekyll.

Мы продолжаем оформлять свой сайт.

# Выполнение лабораторной работы

Мы разместили ссылки на все необходимые ресурсы. (рис. @fig:001).

![Ссылки](image/1.png){#fig:001 width=70%}

Пост на тему по выбору.  (рис. @fig:002).

![Пост на тему по выбору](image/2.png){#fig:002 width=70%}

Недельный пост.  (рис. @fig:003).

![Недельный пост](image/3.png){#fig:003 width=70%}

Измененный сайт.  (рис. @fig:004).

![Измененный сайт](image/4.png){#fig:004 width=70%}

# Выводы

Добавили к сайту данные о себе и два поста.
