---
## Front matter
title: "Отчет по индивидуальному проекту"
subtitle: "Часть 2"
author: "Михайлова Регина Алексеевна"

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

Добавить к сайту данные о себе.

    Список добавляемых данных.
        Разместить фотографию владельца сайта.
        Разместить краткое описание владельца сайта (Biography).
        Добавить информацию об интересах (Interests).
        Добавить информацию от образовании (Education).
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору:
        Управление версиями. Git.
        Непрерывная интеграция и непрерывное развертывание (CI/CD).


# Выполнение проекта

Начинаем с добавления файлов на сайт, а именно с фотографии.

Заходим в папку blog, затем в authors, и в admin (рис. [-@fig:001]). Там меняем данную фотографию на нашу.

![Меняем рисунок](image1.png){#fig:001 width=70%}

Затем займемся данными о себе. В папке admin ищем файл md. Открываем и в первую очередь меняем имена, роль и университет. Потом заполняем интересы (рис. [-@fig:002]).

![Меняем информацию о себе](image2.png){#fig:002 width=70%}

Ищем саму биографию. Придумываем описание и вставляем его в графу. (Рис. [-@fig:003]).

![Биография](image3.png){#fig:003 width=70%}

С биографией покончено. Начинаем делать посты. Ищем папку content, затем переходим в post, оттуда в любую из папок. Начинаем редактирование (рис. [-@fig:004]).

![Папки](image4.png){#fig:004 width=70%}

Тут план действий похожий. Просто меняем информацию на нужную нам и вставляем текст для постов, не забывая вставлять картинки (рис. [-@fig:005]).

![Пост про прошлую неделю](image5.png){#fig:005 width=70%}

![git](image6.png){#fig:006 width=70%}



# Выводы

В ходе лабораторной работы я научилась размещать данные о себе и делать посты на сайте.

# Список литературы{.unnumbered}


