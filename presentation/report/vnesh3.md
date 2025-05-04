---
## Front matter
title: "Прохождение внешнего курса"
subtitle: "Защита пк/телефона"
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

Проработать задания, которые касаются защиты устройств


# Выполнение лабораторной работы

Шифровка загрузочного сектора диска (рис. [-@fig:001]).

![Задание 1](image/3 (15).png){#fig:001 width=70%}

Шифрование диска (рис. [-@fig:002]).

![Задание 2](image/3 (14).png){#fig:002 width=70%}

Программы,жифрующие жесткий диск (рис. [-@fig:003]).

![Задание 3](image/3 (13).png){#fig:003 width=70%}

Стойкие пароли (рис. [-@fig:004]).

![Задание 4](image/3 (12).png){#fig:004 width=70%}

Где безопасно хранить пароли(рис. [-@fig:005]).

![Задание 5](image/3 (11).png){#fig:005 width=70%}

Задача капчи (рис. [-@fig:006]).

![Задание 6](image/3 (10).png){#fig:006 width=70%}

Зачем нужно хэширование паролей (рис. [-@fig:007]).

![Задание 7](image/3 (9).png){#fig:007 width=70%}

Атака протоколов перебором (рис. [-@fig:008]).

![Задание 8](image/3 (8).png){#fig:008 width=70%}

Меры безопасности (рис. [-@fig:009]).

![Задание 9](image/3 (7).png){#fig:009 width=70%}

Фишинговые ссылки (рис. [-@fig:010]).

![Задание 10](image/3 (6).png){#fig:010 width=70%}

Фишинговый email (рис. [-@fig:011]).

![Задание 11](image/3 (5).png){#fig:011 width=70%}

Email Спуфинг (рис. [-@fig:012]).

![Задание 12](image/3 (4).png){#fig:012 width=70%}

Троян (рис. [-@fig:013]).

![Задание 13](image/3 (3).png){#fig:013 width=70%}

Протокол мессенджеров Signal(рис. [-@fig:014]).

![Задание 14](image/3 (2).png){#fig:014 width=70%}

Суть сквозного шифрования (рис. [-@fig:015]).

![Задание 15](image/3 (1).png){#fig:015 width=70%}





# Выводы

Проделаны задания,связаные с защитой устройств
