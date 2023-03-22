---
## Front matter
title: "Проект 2 этап"
subtitle: "НММ-бд-02-22"
author: "Крухмалев Артём Владиславович"


## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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
biblatex: false
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

Научиться работать с сайтом

# Задание

Добавить фотографию, краткую информацию о себе.

# Выполнение проекта

1. Добавим свои фотографии на начальную страницу

![Фото](image/1.png){ #fig:001 width=70% }

2. Заполним папку админ личной информацией 

![Личная информация](image/2.png){ #fig:002 width=70% }

![На странице](image/4.png){ #fig:007 width=70% }

3. Перейдем в папку для написания постов и напишем короткий пост о результатх прошедшей недели

![Пост 1](image/3.png){ #fig:003 width=70% }

![На сайте](image/5.png){ #fig:008 width=70% }

4. Теперем напишем небольшой пост о непрерывной интеграции и непрерывном развертывание

![Пост 2](image/6.png){ #fig:004 width=70% }

5. Зальем все на гитхаб и проверим что все отобразилось исправно.


# Выводы

Второй этап проекта завершен, шинформация добавлена.

:::
