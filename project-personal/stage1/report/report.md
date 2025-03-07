---
# Front matter
title: "Первый этап индивидульного проекта"
subtitle: "Информационная безопасность"
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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью работы является умение установливать операционную систему Kali на виртуальную машину 

# Задание

1. Установка и настрйока ОП	



# Выполнение лабораторной работы

Скачиваю приложение виртуальной машины а также версию Linux Kali, ввожу имя машины, настраиваю количество видео памяти, оперативной памяти, внутренней памяти и кол-во процессоров (рис. [-@fig:001]).

![Создание виртуальной машины](image/1.jpg){#fig:001 width=70%}

Выбираю язык системы (рис. [-@fig:002]).

![Язык системы](image/2.jpg){#fig:002 width=70%}

Указываю имя пользователя-логин (рис. [-@fig:003]).

![Имя пользователя](image/3.jpg){#fig:003 width=70%}

Настраиваю диск,который будет привязан к системе (рис. [-@fig:004]).

![Диск системы](image/4.jpg){#fig:004 width=70%}

Начинаю загрузку (рис. [-@fig:005]).

![Загрузка](image/5.jpg){#fig:005 width=70%}

После перезагрузки запускаю систему (рис. [-@fig:006]).

![Запуск системы](image/6.jpg){#fig:006 width=70%}


# Выводы

Я установил операционную систему.

