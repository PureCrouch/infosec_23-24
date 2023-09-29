---
# Front matter
lang: ru-RU
title: "Лабораторная работа №2"
subtitle: "Математические основы защиты информации и информационной безопасности"
author: "Назарьин Артем Игоревич"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Реализовать шифрование перестановками, шифрование с помощью решеток и таблицы Виженера.


# Выполнение лабораторной работы

## Выполнение задания

Реализую маршрутное шифрование перестановками (рис. -@fig:001 , -@fig:002)

![Маршрутное шифрование, часть 1](image/1.png){ #fig:001 width=50% }

![Маршрутное шифрование, часть 2](image/2.png){ #fig:002 width=50% }

Реализую шифрование с помощью таблицы Виженера. (рис. -@fig:003 , -@fig:004)
Исходный текст: криптография серьезная наука; пароль – математика. Итоговый результат частично не совпал с примером из задания, поскольку в задании была представлена таблица с неполным алфавитом.

![Шифрование с помощью таблицы Виженера, часть 1](image/3.png){ #fig:003 width=50% }

![Шифрование с помощью таблицы Виженера, часть 2](image/4.png){ #fig:004 width=50% }


# Выводы

Я реализовал шифрование перестановками и шифрование с помощью таблицы Виженера.
