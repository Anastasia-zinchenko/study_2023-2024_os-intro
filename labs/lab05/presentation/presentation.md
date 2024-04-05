---
## Front matter
lang: ru-RU
title: Презентация
subtitle: по лабораторной работе № 5
  - Зинченко А.Р
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 15 марта 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

  * Зинченко Анастасия Романовна 
  * НБИбд-01-23
  * Российский университет дружбы народов
  
# Выполнение лабораторной работы

Установила менеджер паролей pass (рис. [-@fig:001]).

![Установка pass](image/001.png){#fig:001 width=50%}

Установила gopass (рис. [-@fig:002]).

![Установка gopass](image/002.png){#fig:002 width=50%}

## Выполнение лабораторной работы

Просмотрела список ключей с помощью команды gpg --list-secret-keys (рис. [-@fig:003]).

![Список ключей](image/003.png){#fig:003 width=50%}

Произвела инициализацию хранилища с помощью команды pass init zinchenkoa06zinchenko@yandex.ru (рис. [-@fig:004]).

![Инициализация](image/004.png){#fig:004 width=50%}

## Выполнение лабораторной работы

Создала структуру git с помощью команды pass git init (рис. [-@fig:005]).

![Инициализация хранилища](image/005.png){#fig:005 width=50%}

Создала репозиторий и назвала его adress. Задала адрес репозитория на хостинге с помощью команды pass git remote add origin git@github.com:<git_username>/<git_repo>.git (рис. [-@fig:006]).

![Адрес репозитория](image/006.png){#fig:006 width=50%}

## Выполнение лабораторной работы

Синхронизировала с помощью команд pass git pull и pass git push (рис. [-@fig:007]).

![Синхронизация](image/007.png){#fig:007 width=50%}
 
Закоммитила и выложила изменения с помощью команд cd ~/.password-store/
git add .
git commit -am 'edit manually'
git push (рис. [-@fig:008]).

![Коммит](image/008.png)

## Выполнение лабораторной работы

Проверила статус синхронизации с помощью команды pass git status (рис. [-@fig:009]).

![Статус синхронизации](image/009.png){#fig:098 width=50%}

Произвела 2 установки с помощью команд dnf copr enable maximbaz/browserpass (рис. [-@fig:010]).

![Установка](image/010.png){#fig:010 width=50%}

## Выполнение лабораторной работы
            
dnf install browserpass (рис. [-@fig:011]).

![Установка](image/011.png){#fig:011 width=50%}

Добавила новый пароль с помощью команды pass insert file.txt (рис. [-@fig:012]).

![Новый пароль](image/012.png){#fig:012 width=50%}

## Выполнение лабораторной работы

Отобразила пароль для file.txt c помощью команды pass file.txt (рис. [-@fig:013]).

![Пароль](image/013.png){#fig:013 width=50%}

Заменила существующий пароль с помощью команды pass generate --in-place file.txt (рис. [-@fig:014]).

![Смена пароля](image/014.png){#fig:014 width=50%}

## Выполнение лабораторной работы

Установила дополнительное программное обеспечение с помощью команд 
    sudo dnf -y install \
       dunst \
       fontawesome-fonts \
       powerline-fonts \
       light \
       fuzzel \
       swaylock \
       kitty \
       waybar swaybg \
       wl-clipboard \
       mpv \
       grim \
       slurp (рис. [-@fig:015]).

![Установка](image/015.png){#fig:015 width=50%}

Установила шрифты с помощью команд sudo dnf copr enable peterwu/iosevka (рис. [-@fig:016]).

![Установка](image/016.png){#fig:016 width=50%}

## Выполнение лабораторной работы
    
sudo dnf search iosevka (рис. [-@fig:017]).

![Установка](image/017.png){#fig:017 width=50%}
    
sudo dnf install iosevka-fonts iosevka-aile-fonts iosevka-curly-fonts iosevka-slab-fonts iosevka-etoile-fonts iosevka-term-fonts (рис. [-@fig:018]).

![Установка](image/018.png){#fig:018 width=50%}


