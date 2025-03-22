---
## Front matter
lang: ru-RU
title: Дискреционное разграничение прав в Linux. Два пользователя
author: |
	 Баптишта Матеуж Андре  НKAбд-01-23\inst{1}

institute: |
	\inst{1}Российский Университет Дружбы Народов

date: 15 марта 2025, Москва, Россия
        
## i18n babel
babel-lang: russian
babel-otherlangs: english

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

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Баптишта Матеуж Андре 
  * Студент, НKAбд-01-23
  * Российский университет дружбы народов
  * [1032225099@pfur.ru](mailto: 1032225099@pfur.ru)

:::
::: {.column width="30%"}

![](image/100.jpg)

:::
:::::::::::::

## Цель лабораторной работы

Получение практических навыков работы в консоли с атрибутами файлов для групп пользователей.

# Процесс выполнения лабораторной работы

## Создание пользователя guest2
 Cоздаем учётную запись пользователя guest2 и его пароль.
 
![создать guest2](image/3.png){ #fig:001 width=70% height=70% }


## Добавление пользователя guest2 в группу guest
gpasswd -a guest2 guest

![Добавление пользователей в группу](image/4.png){ #fig:002 width=70% height=70% }

## Определяем UID и группу двух пользователей

![Информация о пользователях](image/7.png){ #fig:003 width=70% height=70% }


## Атрибуты директории

![атрибуты с директории](image/5.png){ #fig:004 width=70% height=70% }

#Заполнение таблицы
Операции для заполнения таблиц

 ![Заполнение таблицы](image/11.png){ #fig:005 width=70% height=70% }

## Установленные права и разрешенные действия для групп

![Заполнение таблицы 3.1](image/11b.png){ #fig:006 width=70% height=70% }

##Минимальные права для совершения операций

![Заполнение таблицы 3.2](image/11c.png){ #fig:007 width=70% height=70% }


# Выводы по проделанной работе

## Вывод

в этой лаборатории мы узнали, как получить практические навыки работы в консоли с атрибутами файлов для групп пользователей.

