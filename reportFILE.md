---
## Front matter
title: "Прохождение внешнего курса"
subtitle: "Дисциплина: Операционные системы"
author: "Савостин Олег"

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

Целью данной работы является освоение базовых знаний в ОС Linux и пройти внешний курс на Stepik.

# Задание

Пройти курс и получить сертификат.

# Выполнение лабораторной работы

Сперва прохожу первую часть программы курса - Введение. На данном этапе я осваиваю базовый функционал ОС и начинаю работать с интерфейсом, архивами, терминалом. Я освоил несколько полезных навыков с этого этапа курса, такие как запуск исполняемых файлов, скачивание файлов с интернета на Linux и поиск определенных слов в текстовых файлов. Данные навыки помогают более эффективно работать и понять, почему большинство программистов предпочитают Linux вместо Windows (рис. [-@fig:001]).

![1. Введение](image/1.png){#fig:001 width=70%}

Приступаю ко второму этапу, который является сложнее, чем первый этап.На этом этапе курса, я освоил работу на сервере. Я научился выполнять обмен файлами, запуск определенных файлов, контролировать запускаемые программы. Также я освоил Менеджер терминалов tmux (рис. [-@fig:002]).

![2. Работа на сервере](image/2.png){#fig:002 width=70%}

Финальный этап - продвинутые темы является самым трудным для освоения в этом курсе, но помогает новому пользователю свободно работать с ОС Linux. На этом этапе, в задачах были вопросы не только по определениям, но также работа со встроенным терминалом. Надо было писать разные скрипты, выполняющие некоторые действия. Это были скрипты на bash. Я изучил ветвления и циклы. Также научился строить графики в gnuplot. Этот этап курса является самым полезным и интересным по своему содержанию и помогает лучше освоить скрипты. (рис. [-@fig:003]).

![3. Продвинутые темы](image/3.png){#fig:003 width=70%}

Результат (рис. [-@fig:004]).

![Мой результат на курсе.](image/4.png){#fig:004 width=70%}

# Выводы

В итоге, я набрал 120 баллов из 125 за данный курс и получил свой сертификат. Этот курс был очень интересным и помог мне лучше освоить работы в ОС Linux

# Список литературы{.unnumbered}

::: {#refs}
:::
