---
## Front matter
title: "Отчёт индивидуального проекта этапа № 3"
subtitle: "Операционные системы"
author: "Анастасия Романовна Зинченко"

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

Добавить к сайту достижения

# Задание

1. Добавить информацию о навыках (Skills).
2. Добавить информацию об опыте (Experience).
3. Добавить информацию о достижениях (Accomplishments).
4. Сделать пост по прошедшей неделе.
5. Добавить пост по теме: "Языки разметки. LaTeX."

# Выполнение индивидуального проекта

Добавила информацию о навыках (Skills) (рис. [-@fig:001]).

![Skills](image/001.png){#fig:001 width=70%}

Добавила информацию об опыте (Experience) (рис. [-@fig:002]).

![Experience](image/002.png){#fig:002 width=70%}

Добавила информацию о достижениях (Accomplishments) (рис. [-@fig:003]).

![Accomplishments](image/003.png){#fig:003 width=70%}

Сделала пост по прошедшей неделе (рис. [-@fig:004]).

![Пост по прошедшей неделе](image/004.png){#fig:004 width=70%}

Добавила пост по теме: "Языки разметки. LaTeX." (рис. [-@fig:005]).

![LaTeX](image/005.png){#fig:005 width=70%}

# Выводы
 
Я добавила достижения на сайт

# Список литературы{.unnumbered}

::: {#refs}
:::
