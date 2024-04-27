---
## Front matter
title: "Отчёт по лабораторной работе № 12"
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

Изучить основы программирования в оболочке OC UNIX/Linux. Научиться писать небольшие командные файлы.

# Задание

1. Написать скрипт, который при запуске будет делать резервную копию самого себя (то есть файл, в котором содержится его исходный код) в другую директорию backup в моем домашнем каталоге. При этом файл должен архивироваться одним из архиваторов на выбор zip, bzip2, tar. Способ использования команд архивации необходимо узнать, изучив справку. 
2. Написать пример командного файла, обрабатывающего любое произвольное число аргументов командной строки, в том числе превышающее 10. 
3. Написать командный файл - аналог команды ls (без использования самой этой команды и команды dir). Требуется, чтобы он выдавал информацию о нужном каталоге и выводил информацию о возможностях доступа к файлам этого каталога.
4. Написать командный файл, который получает в качестве аргумента командной строки формат файла и вычисляет количество таких файлов в указанной директории. Путь к директории также передаётся в виде аргумента командной строки.

# Выполнение лабораторной работы

Написала скрипт, который при запуске будет делать резервную копию самого себя (то есть файл, в котором содержится его исходный код) в другую директорию backup в моем домашнем каталоге. (рис. [-@fig:001]), (рис. [-@fig: 002]).

![bash1.sh](image/001.png){#fig:001 width=70%}

![Код](image/002.png){#fig:002 width=70%}

Написала пример командного файла, обрабатывающего любое произвольное число аргументов командной строки, в том числе превышающее 10. (рис. [-@fig:003]), (рис. [-@fig: 004]).

![bash2.sh](image/003.png){#fig:003 width=70%}

![Код](image/004.png){#fig:004 width=70%}

Написала командный файл - аналог команды ls (без использования самой этой команды и команды dir). (рис. [-@fig:005]), (рис. [-@fig: 006]).

![bash3.sh](image/005.png){#fig:005 width=70%}

![Код](image/006.png){#fig:006 width=70%}

Написала командный файл, который получает в качестве аргумента командной строки формат файла и вычисляет количество таких файлов в указанной директории. (рис. [-@fig:007]).

![bash4.sh](image/007.png){#fig:007 width=70%}

# Выводы

Я изучила основы программирования в оболочке OC UNIX/Linux. Научилаась писать небольшие командные файлы.


# Список литературы{.unnumbered}

::: {#refs}
:::
