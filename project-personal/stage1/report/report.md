---
## Front matter
title: "Отчёт по индивидуальному проекту этап 1"
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

Разместить на Github pages загатовки для персонального сайта.

# Задание

1. Установить необходимое програмное обеспечение 
2. Скачать шаблон темы сайта 
3. Разместить его на хостинге git 
4.  Установить параметр для URLs сайта 
5. Разместить заготовку сайта на Github pages

# Выполнение лабораторной работы

Скачала исполняемый файл (рис. [-@fig:001]).

![Скачивание исполняемого файла](image/001.jpg){#fig:001 width=70%}

В разделе "Загрузки" извлекла файлы из архива в текущую папку (рис. [-@fig:002]).

![Разархивация](image/002.jpg){#fig:002 width=70%}

В домашнем каталоге создала каталог "bin", после чего перещла в него и вставила "hugo" (рис. [-@fig:003]).

![Создание каталога "bin" и перенос в него "hugo"](image/003.jpg){#fig:003 width=70%}

Перешла в каталог "work", в который склонировала новый репозиторий (рис. [-@fig:004]).

![Клонирование репозитория](image/004.jpg){#fig:004 width=70%}

В каталоге "blog" выполнила команду "~/bin/hugo" (рис. [-@fig:005]).

!["~/bin/hugo"](image/005.jpg){#fig:005 width=70%}

Ввела команду "mc" и выполнила удаление каталога "public" (рис. [-@fig:006]).

![Удаление "public"](image/006.jpg){#fig:006 width=70%}

Далее я ввела команду "~/bin/hugo server" и получила ссылку на свой локальный сайт (рис. [-@fig:007]).

![Ссылка на локальный сайт](image/007.jpg){#fig:007 width=70%}

Перешла на github и создала еще один репозиторий, но уже со специальным названием (рис. [-@fig:008]).

![Создание репозитория со специальным названием](image/008.jpg){#fig:008 width=70%}

Перешла в каталог "work" и склонировала в него свой репозиторий (рис. [-@fig:009]).

![Клонирование репозитория](image/009.jpg){#fig:009 width=70%}

Перешла в новый каталог и переключилась на ветку "main". Создала пустой файл и отправила его на github для активации репозитория (рис. [-@fig:010]).

![Создание пустого файла и добавление его на github](image/010.jpg){#fig:010 width=70%}

Перешла в каталог "blog". Выполнила команду для подключения каталога "public" к новому репозиторию (рис. [-@fig:011]).

![Подключение](image/011.jpg){#fig:011 width=70%}

Запустила команду "mc", нашла ".gitignore" и перешла в него. Прокомментировала "public" (рис. [-@fig:012]).

![Комментирование "public"](image/012.jpg){#fig:012 width=70%}

С помощью команды "cat .gitignore" выполнила проверку, после чего повторила действия с подключением каталога (рис. [-@fig:013]).

![Подключение каталога к новому репозиторию](image/013.jpg){#fig:013 width=70%}

С помощью команды "~/bin/hugo" сгенерировала автоматически файлы в папку "public" (рис. [-@fig:014]).

![Автоматическая генерация файлов](image/014.jpg){#fig:014 width=70%}

Перешла на github и обновила страницу репозитория (рис. [-@fig:015]).

![Обновление репозитория](image/015.jpg){#fig:015 width=70%}

Скопировала ссылку на новый сайт и перешла на него (рис. [-@fig:016]).

![Сайт](image/016.jpg){#fig:016 width=70%}

# Выводы

Я научилась размещать на Github pages заготовки для персонального сайта

# Список литературы{.unnumbered}

::: {#refs}
:::
