---
## Front matter
title: "Индивидуальный проект. Первый этап"
subtitle: "Размещение на Github pages заготовки для персонального сайта"
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
lot: true # List of tables
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

Размещение на Github pages заготовки для персонального сайта.

# Задание

1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
3. Разместить его на хостинге git.
4. Установить параметр для URLs сайта.
5. Разместить заготовку сайта на Github pages.

# Теоретическое введение

Hugo - это генератор статичных сайтов, популярность которого быстро растет. Основанный на языке Go, Hugo создает сайт значительно быстрее, чем большинство других генераторов статических сайтов, включая Jekyll.

# Выполнение лабораторной работы

Для начала нам необходимо скачать hugo_extended_0.98.0_Linux-64bit.tar.gz. (рис. @fig:001).

![Скачивание архива hugo](image/1.png){#fig:001 width=70%}

Теперь разархивируем скаченный архив. (рис. @fig:002).

![Разархивация скаченного архива](image/3.png){#fig:002 width=70%}

Перемещение файла hugo в /usr/local/bin.  (рис. @fig:003).

![Расположение файла hugo](image/2.png){#fig:003 width=70%}

Создаем новый репозиторий blog и клонируем его. (рис. @fig:004).

![Создание и клонирование репозитория](image/4.png){#fig:004 width=70%}

Выполним команду hugo server, по завершению которой мы получим ссылку на наш сайт(на данный момент он виден лишь с моего компьютера). (рис. @fig:005).

![Команда hugo server](image/5.png){#fig:005 width=70%}

Создадим новый репозиторий, для того чтобы наш сайт был виден всем. (рис. @fig:006).

![Создание репозитория aachemodanova.github.io](image/6.png){#fig:006 width=70%}

Клонируем наш новый репозиторий. Создаем ветку main. Создаем файл README.md. Добавляем в наш репозиторий. (рис. @fig:007).

![Клонирование нового репозитория. Создание ветки main. Создание файла README.md](image/7.png){#fig:007 width=70%}

Подключим наш репозиторий к папке public, перед этим исправим ошибку.  (рис. @fig:008).

![Подключение репозитория к папке public](image/9.png){#fig:008 width=70%}

Добавляем файлы в репозиторий.  (рис. @fig:009).

![Добавление файлов в репозиторий](image/11.png){#fig:009 width=70%}


# Выводы

Мы разместили на Github pages заготовки для персонального сайта.

