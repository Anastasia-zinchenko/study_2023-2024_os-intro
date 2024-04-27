---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Этап № 4"
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

Добавить к сайту ссылки на научные и библиометрические ресурсы.

# Задание

Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
        1. eLibrary : https://elibrary.ru/;
        2. Google Scholar : https://scholar.google.com/;
        3. ORCID : https://orcid.org/;
        4. Mendeley : https://www.mendeley.com/;
        5. ResearchGate : https://www.researchgate.net/;
        6. Academia.edu : https://www.academia.edu/;
        7. arXiv : https://arxiv.org/;
        8. github : https://github.com/.
Сделать пост по прошедшей неделе
Добавить пост на тему по выбору: Создание презентаций.

# Выполнение работы

Зарегистрировалась на 8 ресурсах и разместила на них ссылки на сайте (рис. [-@fig:001]).

![Ресурсы](image/001.jpg){#fig:001 width=70%}

Сделала пост по прошедшей неделе (рис. [-@fig:002]).

![Прошедшая неделя](image/002.jpg){#fig:002 width=70%}

Добавила пост по теме "Создание презентаций" (рис. [-@fig:003]).

![Создание презентаций](image/003.jpg){#fig:003 width=70%}

# Выводы

Я добавила к сайту ссылки на научные и библиометрические ресурсы.

# Список литературы{.unnumbered}

::: {#refs}
:::
