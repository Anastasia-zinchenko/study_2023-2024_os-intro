---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Этап 2"
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

Добавить к сайту данные о себе

# Задание

1. Разместить фотографию владельца сайта.
2. Разместить краткое описание владельца сайта (Biography).
3. Добавить информацию об интересах (Interests).
4. Добавить информацию от образовании (Education).
5. Сделать пост по прошедшей неделе.
6. Добавить пост на тему: Управление версиями. Git.
 
# Выполнение лабораторной работы

Я перешла в blog и воспользовалась командой ~/bin/huso server. После перешла по ссылке (рис. [-@fig:001]).

![~/bin/huso server](image/001.png){#fig:001 width=70%}

В папку admin добавила свою фотографию. Подписала ее, как avatar и она заменила ту, которая была изнгачально (рис. [-@fig:002]).

![avatar](image/002.png){#fig:002 width=70%}

После я отредактировала файл _index.md и добавила информацию о себе. А именно биографию (рис. [-@fig:003]).

![Биография](image/003.png){#fig:003 width=70%}

Интересы (рис. [-@fig:004]).

![Интересы](image/004.png){#fig:004 width=70%}

Образование (рис. [-@fig:005]).

![Образование](image/005.png){#fig:005 width=70%}

Далее нужно было создать посты, поэтому в папке post я создала 2 папки, а именно post_1 и post_2 (рис. [-@fig:006]).

![Создание папок](image/006.png){#fig:006 width=70%}

В первую папку я закинула картинку и файл _index.md (рис. [-@fig:007]).

![post_1](image/007.png){#fig:007 width=70%}

Отредактировала _index.md (рис. [-@fig:008]).

![Отредактированный _index.md](image/008.png){#fig:008 width=70%}

Во вторую папку также закинула картинки и файл _index.md (рис. [-@fig:010]).

![post_2](image/010.png){#fig:010 width=70%}

Отредактировала _index.md (рис. [-@fig:009]).

![Отредактированный _index.md](image/009.png){#fig:009 width=70%}

Собрала сайт с помощью команды ~/bin/hugo (рис. [-@fig:011]).

![Сборка сайта](image/011.png){#fig:011 width=70%}

После закинула всё это на github (рис. [-@fig:012]).

![Загрузка на github](image/012.png){#fig:012 width=70%}

Проверила (рис. [-@fig:013]).

![Проверка](image/013.png){#fig:013 width=70%}

# Выводы

Я добавила данные о себе на сайт

# Список литературы{.unnumbered}

::: {#refs}
:::
