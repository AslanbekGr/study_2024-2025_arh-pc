---
## Front matter
title: "Лабораторная работа 2"
subtitle: "Гитхаб"
author: "Хайманов А.С"

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

1. Цель работы   
2. Задание   
3. Теоретическое введение   
4. Выполнение лабораторной работы   
5. Вывод   
6. Список литературы

# Цель работы

Ознакомиться с работой Git, выполнить задания в соответствии с лабораторной работы, а также составить отчет о выполненной работе.

# Задание
1. Изучить документацию приложенную к лабораторной работе   
2. Настроить Гитхаб   
3. Создать SSH ключ, а также рабочее пространство   
4. Создание репозитория и настройка каталога курса   
5. Выполнение заданий для самостоятельной работы   


# Теоретическое введение

Здесь описываются теоретические аспекты, связанные с выполнением работы.

![Теоретический материал 1](image/Теор_1.png){width=100%}    
Теоретический материал 1     

![Теоретический материал 2](image/Теор_2.png){width=100%}    
Теоретический материал 2
# Выполнение лабораторной работы
В пункте 2.4.2 требуется сделать выполнить конфигурацию git (см рис.1)
![Базовая настройка Git (рис 1)](image/Гит.png){width=100%}   
Базовая настройка Git (рис 1)

В пунктах 2.4.3-2.4.4 требуется создать SSH ключ и рабочее пространство(см рис.2)
![Создание ssh ключа (рис 2) (рис 1)](image/Ключ.png){width=100%}   
Создание ssh ключа (рис 2) (рис 1)

![Публичный ssh ключ (рис 3) (рис 1)](image/публичный_ключ.png){width=100%}   
Публичный ssh ключ (рис 3) (рис 1)

![Создание каталога для предмета (рис 4)](image/Создание_каталога.png){width=100%}   
Создание каталога для предмета (рис 4)

В пунктах 2.4.5-2.4.6 требуется создать репозиторию курса и настроить каталог курса (см рис.3-4)
![Клонирование репозитория (рис 5)](image/Клонирование.png){width=100%}   
Клонирование репозитория (рис 5)

![Удаление лишнего файла (рис 6)](image/Удаление.png){width=100%}   
Удаление лишнего файла (рис 6)

![Использование команды make (рис 7)](image/Мейк.png){width=100%}   
Использование команды make (рис 7)

В пункте 2.5 требуется выполнить ряд самостоятельных заданий:   

1) Создать отчет по выполнению лабораторной работы в соответствующим каталоге рабочего пространства   
2) Скопировать отчеты по выполнению предыдущих лабораторных работ в соответствующие каталоги созданного рабочего пространства   
3) Загрузить файлы на гитхаб
    
![Самостоятельная работа (рис 8)](image/Самост.png){width=100%}   
    Самостоятельная работа (рис 8)
    
# Выводы
В процессе выполнения работы, я ознакомился с git. Изучил ряд команд, а также подготовил рабочее пространство.


# Список литературы{.unnumbered}

::: {#refs}
:::
