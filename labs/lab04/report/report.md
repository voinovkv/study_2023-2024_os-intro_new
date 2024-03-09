---
## Front matter
title: "Лабораторная работа № 4"
author: "Воинов Кирилл Викторович"

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

Получение навыков правильной работы с репозиториями git.

# Задание

    Выполнить работу для тестового репозитория.
    Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

# Выполнение лабораторной работы

Установка из коллекции репозиториев Copr. (рис. [-@fig:001] и рис. [-@fig:002]).

![Enable](image/2.png){#fig:001 width=70%}

![Install](image/3.png){#fig:002 width=70%}

Установка Node.js.(рис. [-@fig:003] и рис. [-@fig:004]).

![Install Node](image/4.png){#fig:003 width=70%}

![Install pnpm](image/5.png){#fig:004 width=70%}

Настройка Node.js

(рис. [-@fig:005] и рис. [-@fig:006]).

![Commitizen](image/6.png){#fig:005 width=70%}

![Standard-changelog](image/7.png){#fig:006 width=70%}

Далее команды просто перестали выполнятся.

# Выводы

Получение навыков правильной работы с репозиториями git несостоялось.


