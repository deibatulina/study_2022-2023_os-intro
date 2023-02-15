---
## Front matter
lang: ru-RU
title: Лабораторная работа №2 "Работа с Git"
author:
  - Ибатулина Д.Э.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 15 февраля 2023

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Ибатулина Дарья Эдуардовна
  * студентка группы НКАбд-01-22
  * Российский университет дружбы народов
  * [1132226434@pfur.ru](mailto:1132226434@pfur.ru)
  * <https://github.com/deibatulina>

:::
::: {.column width="30%"}

![](./image/kulyabov.jpg)

:::
::::::::::::::

# Вводная часть

## Актуальность

- Навыки работы с системой контрол версий Git очень важны для программиста или любого другого работника IT сферы;
- Системы контроля версий широко применяются в разработке программ и крупных проектов.

## Объект и предмет исследования

- Презентация как текст
- Программное обеспечение для создания презентаций (pandoc, LaTex)
- Входные и выходные форматы презентаций (md - html, md - pdf)

## Цели и задачи

- Изучить идеологию и применение средств контроля версий. Освоить умения по работе с Git.

- Выполнить приведённые задания и настроить каталог курса.

## Материалы и методы

- Процессор `pandoc` для входного формата Markdown
- Результирующие форматы
	- `pdf`
	- `html`
- Автоматизация процесса создания: `Makefile`

# Создание презентации

## Регистрация на гитхабе

  Для начала я установила Git. Также зарегистрировалась на сайте, создав свою учётную запись на гитхабе и заполнив основную информацию.
  
## Базовая настройка

  Затем я задала гиту необходимые параметры, сгенерировала ssh и gpg ключи и связала свой аккаунт на гитхабе с локальным репозиторием.
  
![Авторизация прошла успешно](image/10.png)

## Создание каталога курса

  Необходимо настроить каталог курса, как указано в соглашении об именовании, связала с локальным репозиторием:

![Настройка каталог курса, переход в него](image/11.png)

  Теперь все лабораторные работы будут храниться там.
  
## Итог работы

  Теперь я смогу добавлять все изменённые файлы и каталоги на свой репозиторий на гитхабе посредством локального репозитория. Это безусловно очень удобно.

## Результаты

  - Я научилась работать с системой контроля версий Git;
  - Узнала о ней новую информацию, сделала базовую настройку, научилась базовым командам.

## Итоговый слайд

- Системы контроля версий - безусловно очень удобная вещь. Они позволяют организовать данные в определённую структуру и делать откат к более ранним версиям, не удаляя при этом все остальные.
