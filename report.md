---
## Front matter
title: "Отчёт по проекту"
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

Отчет написан чтобы показать выполнение задач на курсе Степика. В видео показано, как автор выполняет курс.

# Задание

1. Задания

# Выполнение лабораторной работы

Выбор не влияет на результат.(рис. [-@fig:001])

![Выбор не влияет на результат](image/1.png){#fig:001 width=70%}

Определение ОС.(рис. [-@fig:002])

![Определение ОС](image/2.png){#fig:002 width=70%}

Виртуальная машина.(рис. [-@fig:003])

![Виртуальная машина](image/3.png){#fig:003 width=70%}


Расширение установочных пакетов.(рис. [-@fig:004])

![Расширение установочных пакетов](image/4.png){#fig:004 width=70%}

Для чего используют Update Manager.(рис. [-@fig:005])

![Для чего используют Update Manager](image/5.png){#fig:005 width=70%}

Синонимы командной строки.(рис. [-@fig:006])

![Синонимы командной строки](image/6.png){#fig:006 width=70%}

Вывод директории нахождения.(рис. [-@fig:007])

![Вывод директории нахождения](image/7.png){#fig:007 width=70%}

Команды выбранные в списке являются эквивалентны команде, указанной в задании.(рис. [-@fig:008])

![Команды выбранные в списке являются эквивалентны команде, указанной в задании](image/8.png){#fig:008 width=70%}

Быстрый переход в другую папку.(рис. [-@fig:009])

![Быстрый переход в другую папку](image/9.png){#fig:009 width=70%}

Команда для удаления директорий.(рис. [-@fig:010])

![Команда для удаления директорий](image/10.png){#fig:010 width=70%}

.(рис. [-@fig:011])

![Никто не закроется](image/11.png){#fig:011 width=70%}

Запуск, Ctrl+Z, bg эквивалентен запуску программы с &.(рис. [-@fig:012])

![Запуск, Ctrl+Z, bg эквивалентен запуску программы с &](image/12.png){#fig:012 width=70%}

.(рис. [-@fig:013])

![-](image/13.png){#fig:013 width=70%}

.(рис. [-@fig:014])

![Выводится на экран](image/14.png){#fig:014 width=70%}

Команды создающие файл и которые запишут в него поток ошибок.(рис. [-@fig:015])

![Команды создающие файл и которые запишут в него поток ошибок](image/15.png){#fig:015 width=70%}

Сообщения об ошибках выводятся на экран.(рис. [-@fig:016])

![Сообщения об ошибках выводятся на экран](image/16.png){#fig:016 width=70%}

В файле 1.jpg.(рис. [-@fig:017])

![В файле 1.jpg](image/17.png){#fig:017 width=70%}

Роль -q --quiet.(рис. [-@fig:018])

![Роль -q --quiet](image/18.png){#fig:018 width=70%}

Будут скачаны jpg html.(рис. [-@fig:019])

![Будут скачаны jpg html](image/19.png){#fig:019 width=70%}

Разница между gzip zip.(рис. [-@fig:020])

![Разница между gzip zip](image/20.png){#fig:020 width=70%}

tar zip.(рис. [-@fig:021])

![tar zip](image/21.png){#fig:021 width=70%}

-cjf.(рис. [-@fig:022])

![-cjf](image/22.png){#fig:022 width=70%}

finв * .jpg найдет только файлы jpg, a ne jpeg. alexey.* начинается с прописной а, а надо с заглавной. *? из-за вопросительного знака.(рис. [-@fig:023])

![find *.jpg найдет только файлы jpg, a ne jpeg. alexey.* начинается с прописной а, а надо с заглавной. *? изза вопросительного знака](image/23.png){#fig:023 width=70%}

Все отмеченные варианты имеют комбинацию букв world,  что и ищет команда..(рис. [-@fig:024])

![Все отмеченные варианты имеют комбинацию букв world,  что и ищет команда.](image/24.png){#fig:024 width=70%}

Все варианты.(рис. [-@fig:025])

![Все варианты](image/25.png){#fig:025 width=70%}

id_rsa.pub.(рис. [-@fig:026])

![id_rsa.pub](image/26.png){#fig:026 width=70%}

Данная команда скопирует на сервер папку..(рис. [-@fig:027])

![Данная команда скопирует на сервер папку.](image/27.png){#fig:027 width=70%}

sudo apt-get update обновит команду и исправит проблему.(рис. [-@fig:028])

![sudo apt-get update обновит команду и исправит проблему](image/28.png){#fig:028 width=70%}

Filezilla.(рис. [-@fig:029])

![Filezilla](image/29.png){#fig:029 width=70%}

.(рис. [-@fig:030])

![-](image/30.png){#fig:030 width=70%}

команды информационные.(рис. [-@fig:031])

![команды информационные](image/31.png){#fig:031 width=70%}

.(рис. [-@fig:032])

![-](image/32.png){#fig:032 width=70%}

.(рис. [-@fig:033])

![-](image/33.png){#fig:033 width=70%}

.(рис. [-@fig:034])

![-](image/34.png){#fig:034 width=70%}

.(рис. [-@fig:035])

![-](image/35.png){#fig:035 width=70%}

kill -9.(рис. [-@fig:036])

![kill -9](image/36.png){#fig:036 width=70%}

.(рис. [-@fig:037])

![-](image/37.png){#fig:037 width=70%}

.(рис. [-@fig:038])

![-](image/38.png){#fig:038 width=70%}

.(рис. [-@fig:039])

![-](image/39.png){#fig:039 width=70%}

.(рис. [-@fig:040])

![-](image/40.png){#fig:040 width=70%}

.(рис. [-@fig:041])

![-](image/41.png){#fig:041 width=70%}

.(рис. [-@fig:042])

![-](image/42.png){#fig:042 width=70%}

.(рис. [-@fig:043])

![-](image/43.png){#fig:043 width=70%}

.(рис. [-@fig:044])

![-](image/44.png){#fig:044 width=70%}

tmux не прекратит работать при отсоединения от сервера.(рис. [-@fig:045])

![tmux не прекратит работать при отсоединения от сервера](image/45.png){#fig:045 width=70%}

Завершится весь процесс при закрытии вкладки.(рис. [-@fig:046])

![Завершится весь процесс при закрытии вкладки](image/46.png){#fig:046 width=70%}

.(рис. [-@fig:047])

![-](image/47.png){#fig:047 width=70%}

.(рис. [-@fig:048])

![-](image/48.png){#fig:048 width=70%}

.(рис. [-@fig:049])

![-](image/49.png){#fig:049 width=70%}

Текстовый редактор vim.(рис. [-@fig:050])

![Текстовый редактор vim](image/50.png){#fig:050 width=70%}

.(рис. [-@fig:051])

![-](image/51.png){#fig:051 width=70%}

.(рис. [-@fig:052])

![-](image/52.png){#fig:052 width=70%}

.(рис. [-@fig:053])

![-](image/53.png){#fig:053 width=70%}

.(рис. [-@fig:054])

![-](image/54.png){#fig:054 width=70%}

Что выведет данный скрипт.(рис. [-@fig:055])

![Что выведет данный скрипт](image/55.png){#fig:055 width=70%}

variables.(рис. [-@fig:056])

![variables](image/56.png){#fig:056 width=70%}

Первый скрипт на курсе.(рис. [-@fig:057])

![Первый скрипт на курсе](image/57.png){#fig:057 width=70%}

.(рис. [-@fig:058])

![-](image/58.png){#fig:058 width=70%}

.(рис. [-@fig:059])

![-](image/59.png){#fig:059 width=70%}

Второй скрипт выводит текст, который зависит от количества студентов.(рис. [-@fig:060])

![Второй скрипт выводит текст, который зависит от количества студентов](image/60.png){#fig:060 width=70%}

.(рис. [-@fig:061])

![-](image/61.png){#fig:061 width=70%}

Данный скрипт распределяет пользователя на группы - child, youth, adult(рис. [-@fig:062])

![Данный скрипт распределяет пользователя на группы - child, youth, adult](image/62.png){#fig:062 width=70%}

.(рис. [-@fig:063])

![-](image/63.png){#fig:063 width=70%}

.(рис. [-@fig:064])

![-](image/64.png){#fig:064 width=70%}

.(рис. [-@fig:065])

![-](image/65.png){#fig:065 width=70%}

.(рис. [-@fig:066])

![-](image/66.png){#fig:066 width=70%}

Данный скрипт ищет НОД (Наибольший общий делитель)(рис. [-@fig:067])

![Данный скрипт ищет НОД (Наибольший общий делитель)](image/67.png){#fig:067 width=70%}

.(рис. [-@fig:068])

![-](image/68.png){#fig:068 width=70%}

.(рис. [-@fig:069])

![-](image/69.png){#fig:069 width=70%}

.(рис. [-@fig:070])

![-](image/70.png){#fig:070 width=70%}

.(рис. [-@fig:071])

![-](image/71.png){#fig:071 width=70%}

.(рис. [-@fig:072])

![-](image/72.png){#fig:072 width=70%}

.(рис. [-@fig:073])

![-](image/73.png){#fig:073 width=70%}

.(рис. [-@fig:074])

![-](image/74.png){#fig:074 width=70%}

.(рис. [-@fig:075])

![-](image/75.png){#fig:075 width=70%}

.(рис. [-@fig:076])

![-](image/76.png){#fig:076 width=70%}

.(рис. [-@fig:077])

![-](image/77.png){#fig:077 width=70%}

.(рис. [-@fig:078])

![-](image/78.png){#fig:078 width=70%}

.(рис. [-@fig:079])

![-](image/79.png){#fig:079 width=70%}

.(рис. [-@fig:080])

![-](image/80.png){#fig:080 width=70%}

.(рис. [-@fig:081])

![-](image/81.png){#fig:081 width=70%}

.(рис. [-@fig:082])

![-](image/82.png){#fig:082 width=70%}

.(рис. [-@fig:083])

![-](image/83.png){#fig:083 width=70%}

# Выводы

Я не ответил на все вопросы в данном курсе, однако, я получил сертификат с отличием.

# Список литературы{.unnumbered}

::: {#refs}
:::
