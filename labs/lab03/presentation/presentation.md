---
## Front matter
lang: ru-RU
title: Презентация лабораторной работы
subtitle: Лабораторная №3
author:
  - Барабаш П. В.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 20 марта 2026

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
 
 
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9

---

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Барабаш Полина Витальевна
  * студентка 2 курса, НПИбд-01-24
  * Российский университет дружбы народов
  * [1132231841@rudn.ru](mailto:1132231841@rudn.ru)

:::
::: {.column width="30%"}

![](./image/я.png)

:::
::::::::::::::

## Цели и задачи

Цель: получение практических навыков работы в консоли с атрибутами файлов для групп пользователей


## Создание пользователей

![](./image/fig001.png)



## Добавление пользователя guest2 в группу guest


![](./image/fig002.png)


## Информация команд id и groups и файлу /etc/group

![](./image/fig005.png)


## Добавление прав для пользователей групп на guest

![](./image/fig007.png)


## Добавление прав на dir1

![](./image/fig008.png)

## Права доступа

- 010 -- исполнение пользователями групп

- 020 -- запись пользователями групп

- 030 -- исполнение + запись пользователями групп

- 040 -- чтение пользователями групп

- 050 -- исполнение + чтение пользователями групп

- 060 -- запись + чтение пользователями групп

- 070 -- исполнение + запись + чтение пользователями групп

## Пример выполнения основного задания

![](./image/fig060.png)

## Результаты, ч.1

![](./image/tabl1.png)

## Результаты, ч.2

![](./image/tabl2.png)

## Результаты, ч.3

![](./image/tabl3.png)

## Минимальные права для совершения операций

![](./image/tabl4.png)

## Выводы

Я получила практические навыки работы в консоли с атрибутами файлов для групп пользователей.
