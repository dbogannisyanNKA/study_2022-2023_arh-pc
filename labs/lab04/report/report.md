---
## Front matter
title: "Отчёт по лабораторной работе № 4"
subtitle: "Язык разметки Markdown"
author: "Оганнисян Давит Багратович"

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

Целью работы является освоение процедуры оформления отчетов с помощью
легковесного языка разметки Markdown.


# Теоретическое введение

## Базовые сведения о Markdown
## Оформление формул в Markdown
## Оформление изображений в Markdown
## Обработка файлов в формате Markdown
## Техническое обеспечение
# Выполнение лабораторной работы

## Откройте терминал и перейдите в каталог курса сформированный при выполнении лабораторной работы No3

![Каталог курса ЛР№3](image/1.jpg){ #fig:001 width=70% }

## Обновите локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды

![git pull](image/2.jpg){ #fig:002 width=70% }

## Перейдите в каталог с шаблоном отчета по лабораторной работе No 4 и проведите компиляцию шаблона с использованием Makefile. 

![make](image/3.jpg){ #fig:003 width=70% }

![Проверка](image/4.jpg){ #fig:004 width=70% }

## Удалите полученный файлы с использованием Makefile. Для этого и проверьте, что после этой команды файлы report.pdf и report.docx были удалены.

![make clear](image/5.jpg){ #fig:005 width=70% }

![Проверка](image/6.jpg){ #fig:006 width=70% }

## Откройте файл report.md c помощью любого текстового редактора.

![gedit](image/8.jpg){ #fig:008 width=70% }

![report.md](image/7.jpg){ #fig:007 width=70% }

## После заполнения отчета загрузите файлы на Github

![Загрузка файлов](image/11.jpg){ #fig:011 width=70% }

## Задание для самостоятельной работы

![make №3](image/9.jpg){ #fig:009 width=70% }

![Загрузка файлов №3](image/10.jpg){ #fig:010 width=70% }



# Выводы

Я научился пользоваться Markdown-ом

