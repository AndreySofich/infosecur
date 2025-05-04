---
## Front matter
title: "Прохождение внешнего курса"
subtitle: "Безопасность в сети"
author: "Софич Андрей Геннадьевич"

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

Проработать задания, которые касаются безопасности в сети


# Выполнение лабораторной работы

1 задание, думаю,особые комментарии тут излишни (рис. [-@fig:001]).

![Задание 1](image/2 (22).png){#fig:001 width=70%}

Уровень протокола TCP (рис. [-@fig:001]).

![Задание 2](image/2 (21).png){#fig:002 width=70%}

Корректные адреса IPv4 (рис. [-@fig:002]).

![Задание 3](image/2 (20).png){#fig:003 width=70%}

Главная задача DNS сервера (рис. [-@fig:003]).

![Задание 4](image/2 (19).png){#fig:004 width=70%}

Последовательность многих протоколов идентична у TCP/IP такой (рис. [-@fig:005]).

![Задание 5](image/2 (18).png){#fig:005 width=70%}

Задача протокола http (рис. [-@fig:006]).

![Задание 6](image/2 (17).png){#fig:006 width=70%}

Структура протокола http (рис. [-@fig:007]).

![Задание 7](image/2 (16).png){#fig:007 width=70%}

Версия протокола TLS (рис. [-@fig:008]).

![Задание 8](image/2 (15).png){#fig:008 width=70%}

Фаза протокола TLS (рис. [-@fig:009]).

![Задание 9](image/2 (14).png){#fig:009 width=70%}

Что хранят куки (рис. [-@fig:010]).

![Задание 10](image/2 (13).png){#fig:010 width=70%}

Для куки не используются (рис. [-@fig:011]).

![Задание 11](image/2 (12).png){#fig:011 width=70%}

Чем генерируется куки (рис. [-@fig:012]).

![Задание 12](image/2 (11).png){#fig:012 width=70%}

Куки хранятся только до использования веб сайтом (рис. [-@fig:013]).

![Задание 13](image/2 (10).png){#fig:013 width=70%}

Сеть TOR (рис. [-@fig:014]).

![Задание 14](image/2 (9).png){#fig:014 width=70%}

IP получателя (рис. [-@fig:015]).

![Задание 15](image/2 (8).png){#fig:015 width=70%}

Какой ключ генерирует отправитель (рис. [-@fig:016]).

![Задание 16](image/2 (7).png){#fig:016 width=70%}

Получение пакетов (рис. [-@fig:017]).

![Задание 17](image/2 (6).png){#fig:017 width=70%}

Wi-fi (рис. [-@fig:018]).

![Задание 18](image/2 (5).png){#fig:018 width=70%}

Уровень wi-fi (рис. [-@fig:019]).

![Задание 19](image/2 (4).png){#fig:019 width=70%}

Шифрование(рис. [-@fig:020]).

![Задание 20](image/2 (3).png){#fig:020 width=70%}

Между хостом и роутером (рис. [-@fig:021]).

![Задание 20](image/2 (2).png){#fig:021 width=70%}

Метод для домашней сети (рис. [-@fig:022]). 

![Задание 21](image/2 (1).png){#fig:022 width=70%}


# Выводы

Проделаны задания,связаны с безопастностью в сети
