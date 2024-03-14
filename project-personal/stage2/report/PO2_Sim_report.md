---
## Front matter
title: "Отчёт по 2 этапу индивидуального проекта"
subtitle: "Операционные системы"
author: "Симонова Вивтория Игоревна"

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

Продолжить работы со своим сайтом. Редактировать его в соответствии с требованиями. Добавить данные о себе.

# Задание

Добавить на сайт информацию 
Список добавляемых данных.
* Разместить фотографию владельца сайта.
* Разместить краткое описание владельца сайта (Biography).
* Добавить информацию об интересах (Interests).
** Добавить информацию от образовании (Education).
** Сделать пост по прошедшей неделе.
** Добавить пост на тему по выбору:
** Управление версиями. Git.
** Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Выполнение лабораторной работы

Меняю фотографию на свою (рис. [-@fig:001]).

![Моё фото](image/1.png){#fig:001 width=70%}

Изменяю информацию сайта на информацию о себе (рис. [-@fig:002]).

![Личная информация](image/2.png){#fig:002 width=70%}

Информация о моём образнии (рис. [-@fig:003]).

![Личная информация](image/3.png){#fig:003 width=70%}

Проверяю, что всё получилось (рис. [-@fig:004]).

![Что в итоге получилось](image/4.png){#fig:004 width=70%}

Создаю паку для поста с информацией о моей прошедшей неделе (рис. [-@fig:005]).

![Пост о неделе](image/5.png){#fig:005 width=70%}

Пишу пост (рис. [-@fig:006]).

![Пост о неделе](image/6.png){#fig:006 width=70%}

Проверяю, что пост выложен на сайте (рис. [-@fig:007]).

![Пост о неделе на сайте](image/7.png){#fig:007 width=70%}

Содержание поста тоже синхронизировалось, ссылки работают картинки есть (рис. [-@fig:008]).

![Пост о неделе на сайте](image/8.png){#fig:008 width=70%}

Создаю паку для поста с информацией о версионировании гит (рис. [-@fig:009]).

![Пост о контроле версий](image/9.png){#fig:009 width=70%}

Пишу пост (рис. [-@fig:010]).

![Пост о контроле версий](image/10.png){#fig:010 width=70%}

Проверяю, что пост выложен на сайте (рис. [-@fig:011]).

![Пост о контроле версий на сайте](image/11.png){#fig:011 width=70%}

Содержание поста тоже синхронизировалось, ссылки работают (рис. [-@fig:012]).

![Пост о нконтроле версий на сайте](image/12.png){#fig:012 width=70%}

Отправляю изменения на гитхаб (рис. [-@fig:013]).

![Отправка изменений](image/13.png){#fig:013 width=70%}

Отправляю изменения из папки public, чтобы сайт был доступен не только с хостинга (рис. [-@fig:014]).

![Пост о нконтроле версий на сайте](image/14.png){#fig:014 width=70%}

Открываю сайт в браузере chrome, основной операционной системы, тем самым убеждаюсь, что ссылка работает (рис. [-@fig:015]).

![Мой сайт](image/15.png){#fig:015 width=70%}

# Выводы

Здесь кратко описываются итоги проделанной работы.

# Список литературы{.unnumbered}

::: {#refs}
:::
