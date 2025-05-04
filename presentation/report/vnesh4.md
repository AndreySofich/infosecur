---
## Front matter
title: "Прохождение внешнего курса"
subtitle: "Криптография на практике"
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

Проработать задания, которые касаются криптографии


# Выполнение лабораторной работы

Ассимитричные криптографические примитивы (рис. [-@fig:001]).

![Задание 1](image/4 (16).png){#fig:001 width=70%}

Хэш-функция (рис. [-@fig:002]).

![Задание 2](image/4 (15).png){#fig:002 width=70%}

Алгоритмы цифровой подписи (рис. [-@fig:003]).

![Задание 3](image/4 (14).png){#fig:003 width=70%}

Код аунтетификации сообщения (рис. [-@fig:004]).

![Задание 4](image/4 (13).png){#fig:004 width=70%}

Обмен ключами Диффи-Хэлмана (рис. [-@fig:005]).

![Задание 5](image/4 (12).png){#fig:005 width=70%}

Протокол электронной цифровой подписи  (рис. [-@fig:006]).

![Задание 6](image/4 (11).png){#fig:006 width=70%}

Алгоритм верификации электронной цифровой подписи (рис. [-@fig:007]).

![Задание 7](image/4 (10).png){#fig:007 width=70%}

Подпись(рис. [-@fig:008]).

![Задание 8](image/4 (9).png){#fig:008 width=70%}

Тип сертификата электронной подписи в ФНС  (рис. [-@fig:009]).

![Задание 9](image/4 (8).png){#fig:009 width=70%}

Организация (рис. [-@fig:010]).

![Задание 10](image/4 (7).png){#fig:010 width=70%}

Платежные системы (рис. [-@fig:011]).

![Задание 11](image/4 (6).png){#fig:011 width=70%}

Многофакторная аунтетификация (рис. [-@fig:012]).

![Задание 12](image/4 (5).png){#fig:012 width=70%}

Онлайн платежи сегодня (рис. [-@fig:013]).

![Задание 13](image/4 (4).png){#fig:013 width=70%}

Свойство криптографичской хэш-функции (рис. [-@fig:014]).

![Задание 14](image/4 (3).png){#fig:014 width=70%}

Свойства консенсуса в системах блокчейн (рис. [-@fig:015]).

![Задание 15](image/4 (2).png){#fig:015 width=70%}

Секретные ключи (рис. [-@fig:015]).

![Задание 15](image/4 (1).png){#fig:016 width=70%}





# Выводы

Проделаны задания,связаные с криптографией
