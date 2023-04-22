---
## Front matter
title: "Отчёт по четвёртому этапу индивидуального проекта"
subtitle: "Персональный сайт научного работника"
author: "Дарья Эдуардовна Ибатулина"

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

  Научиться добавлять ссылки к сайту, попрактиковаться в написании постов.

# Задание

  Необходимо:

* зарегистрироваться на указаных ресурсах и добавить их ссылки на сайт;
* добавить пост на тему по выбору;
* сделать пост по прошедшей неделе.

# Теоретическое введение

  Сайт, или веб-сайт (от англ. website: web — «паутина, сеть» и site — «место», букв. — «место, сегмент, часть в сети»), также веб-узел, — одна или несколько логически связанных между собой веб-страниц; также место расположения контента сервера. Обычно сайт в Интернете представляет собой массив связанных данных, имеющий уникальный адрес и воспринимаемый пользователями как единое целое. Веб-сайты называются так, потому что доступ к ним происходит по протоколу HTTP.
  
  Индивидуальный проект подразумевает размещение заготовки персонального сайта научного работника на GithubPages - сайт, созданный в репозитории GitHub.
  
  На сайте пользователь может размещать фотографии, посты, публиковать информацию о себе и указывать способы связи. Контент сайта зависит от его тематики и цели создания.
  
  При создании сайта я буду использовать язык разметки YAML, который расшифровывается как "ещё один язык разметки".

# Выполнение лабораторной работы

  Для начала добавим к сайту ссылки (рис. @fig:001).

![Добавление ссылок к сайту](image/1.png){#fig:001 width=70%}

Описываются проведённые действия, в качестве иллюстрации даётся ссылка на иллюстрацию (рис. @fig:002).

![Пост по прошедшей неделе](image/2.png){#fig:002 width=70%}

Описываются проведённые действия, в качестве иллюстрации даётся ссылка на иллюстрацию (рис. @fig:003).

![Пост на тему: "Оформление отчётов"](image/3.png){#fig:003 width=70%}

# Выводы

  В результате выполнения 4-го этапа индивидуального проекта я попрактиковалась в написании постов, научилась добавлять ссылки на сайт.

# Список литературы{.unnumbered}

::: {#refs}
:::
