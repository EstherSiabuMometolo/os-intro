---
## Front matter
title: "Отчёт по 1 этапу проекта"
subtitle: "Сайт научного работника"
author: "Сиабу Мометоло Эстер"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Подготовить репозиторий на основе шаблона. Ознакомиться с генератором сайтов hugo.

# Выполнение работы

Клонирую репозиторий с шаблоном сайта-визитки.

![Создание репозитория из шаблона](image/01.png){ #fig:001 width=70% height=70%}

Создаю локальные репозитории для размещение сайта.

![Создание локальных репозиториев](image/02.png){ #fig:002 width=70% height=70%}

Тестирую запуск hugo.

![Инициализация hugo](image/03.png){ #fig:003 width=70% height=70%}

Подготовка репозитория для файлов сайта.

![Подготовка репозитория](image/04.png){ #fig:004 width=70% height=70%}

Связывание папки public с подготовленным репозиторием.

![Подготовка папки public](image/05.png){ #fig:005 width=70% height=70%}

Развертывание сайта на основе HitHub Pages.

![Развертывание сайта](image/06.png){ #fig:006 width=70% height=70%}

# Выводы

Подготовили репозиторий и установили hugo.