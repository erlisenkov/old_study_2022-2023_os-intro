---
## Front matter
title: Лабораторная работа №3
subtitle: Операционные системы
author: Лисенков Егор, НКАбд-03-23

## Generic otions
lang: ru-RU
toc-title: "Содержание"
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 28 февраля 2024

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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

1. Понять базовые принципы работы с языком разметки Markdown.

# Выполние лабораторной работы

Выполним небольшую корректировку в файле md (из шаблона), для того чтобы были мои данные. (рис. [-@fig:001])

![Настройка файла md](image/1.png){#fig:001 width=70%}

Заполню верхние поля нашей лабораторной работы. (рис. [-@fig:002])

![Редактирование](image/2.png){#fig:002 width=70%}

Начну писать основной текст для лабораторной работы. (рис. [-@fig:003])

![Редактирование](image/3.png){#fig:003 width=70%}

Буду вставлять фото по этому образцу для нашего отчёта. (рис. [-@fig:004])

![Редактирование](image/4.png){#fig:004 width=70%}

Заполним конечный этап нашего отчёта с помощью списка литературы. (рис. [-@fig:005])

![Конец](image/5.png){#fig:005 width=70%}

# Вывод

В результате выполнения лабораторной работы я научился оформлять отчеты с помощью легковесного языкаразметки Markdown.
