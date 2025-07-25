---
## Front matter
title: "Отчёт по лабораторной работе №9"
subtitle: "Командная оболочка Midnight Commander"
author: "Сиабу Мометоло Эстер"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Освоение основных возможностей командной оболочки Midnight Commander.
Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Выполнение лабораторной работы

1 Изучим информацию о mc при помощи справки man.
Воспользуемся справкой и узнаем что для того чтобы войти в командную оболочку мы должны ввести в командной строке mc.

2 Запустим из командной строки mc.

![Запуск mc](image/01.png){ #fig:001 width=70% height=70% }

3 Выполните несколько операций в mc, используя управляющие клавиши

![Выделение](image/02.png){ #fig:002 width=70% height=70% }

![Отмена](image/03.png){ #fig:003 width=70% height=70% }

![Копирование](image/04.png){ #fig:004 width=70% height=70% }

![Перемещение](image/05.png){ #fig:005 width=70% height=70% }

![Информация](image/06.png){ #fig:006 width=70% height=70% }

4 Выполните основные команды меню левой панели. 

![Быстрый просмотр](image/07.png){ #fig:007 width=70% height=70% }

![Информация](image/08.png){ #fig:008 width=70% height=70% }

![Дерево каталогов](image/09.png){ #fig:009 width=70% height=70% }

5 Используя возможности подменю Файл , выполним:

![Просмотр содержимого текстового файла](image/10.png){ #fig:010 width=70% height=70% }

![Отредактируем содержимое текстового файла без сохранения результатов](image/11.png){ #fig:011 width=70% height=70% }

![Создание каталога ](image/12.png){ #fig:012 width=70% height=70% }

![Копирование в файлов в созданный каталог](image/13.png){ #fig:013 width=70% height=70% }

6. С помощью соответствующих средств подменю Команда осуществите: 

![Поиск файлов](image/14.png){ #fig:014 width=70% height=70% }

![История команд](image/15.png){ #fig:015 width=70% height=70% }

![Переход в домашний каталог](image/16.png){ #fig:016 width=70% height=70% }

![Просмотр файла расширений](image/17.png){ #fig:017 width=70% height=70% }

![Просмотр файла меню](image/18.png){ #fig:018 width=70% height=70% }

7. Вызовем подменю Настройки. Изучим опции

![Конфигурация](image/19.png){ #fig:019 width=70% height=70% }

![Внешний вид](image/20.png){ #fig:020 width=70% height=70% }

![Настройки панелей](image/21.png){ #fig:021 width=70% height=70% }

![Подтверждение](image/22.png){ #fig:022 width=70% height=70% }

![Оформление](image/23.png){ #fig:023 width=70% height=70% }

![Кодировка символов](image/24.png){ #fig:024 width=70% height=70% }

![Распознавание клавиш](image/25.png){ #fig:025 width=70% height=70% }

8 Создадим текстовой файл text.txt. 

9 Откроем этот файл с помощью встроенного в mc редактора, и вставим в открытый файл небольшой фрагмент текста, скопированный из любого другого файла или Интернета. 

![Файл с текстом](image/26.png){ #fig:026 width=70% height=70% }

10 Проделаем с текстом следующие манипуляции, используя горячие клавиши:

Удалим строку текста. - F8

![Файл с текстом](image/27.png){ #fig:027 width=70% height=70% }

Выделим фрагмент текста и скопируйте его на новую строку. - F5

![Копирование фрагмента](image/28.png){ #fig:028 width=70% height=70% }

Сохраним файл. - F2

![Сохранение](image/29.png){ #fig:029 width=70% height=70% }

Отменим последнее действие. - Ctrl+U

![Отмена](image/30.png){ #fig:030 width=70% height=70% }

Перейдем в конец файла - PageDown или Ctrl+X

![Переход в конец файла](image/31.png){ #fig:031 width=70% height=70% }

Перейдем в начало файла - PageUp или Ctrl+Z

![Переход в начало файла](image/32.png){ #fig:032 width=70% height=70% }

11 Откроем файл с исходным текстом на языке программирования C

![Файл с программой](image/33.png){ #fig:033 width=70% height=70% }

12 Используя меню редактора, выключим подсветку синтаксиса.

![Цветовыделение синтаксиса](image/34.png){ #fig:034 width=70% height=70% }

# Вывод

В данной работе мы ознакомились с инструментами командной оболочки Midnight Commander. Приобрели навыки практической работы по просмотру каталогов и файлов 

# Контрольные вопросы

1. Какие режимы работы есть в mc? Охарактеризуйте их.
Ответ: В командной оболочке mc есть два режима Информация и Дерево. В режиме Информация на панель выводятся сведения о файле и текущей файловой системе, расположенных на активной панели. В режиме Дерево на одной из панелей выводится структура дерева каталогов. Управлять режимами отображения панелей можно через пункты меню mc

2. Какие операции с файлами можно выполнить как с помощью команд shell, так и с помощью меню mc? Привести несколько примеров.
Ответ: Командные интерпретатор Shell и оболочка Midnight Commander имеют похожую структуру и многие одинаковые команды можно выполнить в обоих оболочках вот некоторые из них
a) Системная информация
b) Поиск
c) Копирование

3. Опишите структуру меню левой панели mc, дайте характеристику командам.
Ответ: Меню левой панели mc представляет собой следующую конструкцию:

Где подпункты меню
a) Список файлов показывает файлы в домашнем каталоге.
b) Быстрый просмотр позволяет выполнить быстрый просмотр содержимого панели.     
с) Информация позволяет посмотреть информацию о файле или каталоге 
d) Командная оболочка Midnight Commander В меню каждой (левой или правой) панели можно выбрать Формат списка: стандартный, ускоренный, расширенный  и определённый пользователем.
e) Порядок сортировки позволяет задать критерии сортировки при выводе списка файлов и каталогов: без сортировки, по имени, расширенный, время правки, время доступа, время изменения атрибута, размер, узел.

4. Опишите структура меню Файл mc и дайте характеристику командам.
Ответ: Меню Фаил mc представляет собой следующую конструкцию:

Где подпункты меню
a) Просмотр ( F3 )  позволяет посмотреть содержимое текущего файла без возможности редактирования. 
b) – Просмотр вывода команды ( М + ! ) функция запроса команды с параметрами.
c) Правка ( F4 ) открывает текущий (или выделенный) файл для его редактирования. 
d) Копирование ( F5 ) осуществляет копирование одного или нескольких файлов или каталогов в указанное пользователем во всплывающем окне место. 
e) Права доступа ( Ctrl-x c ) позволяет изменить права доступа к одному или нескольким файлам или каталогам.
f)  Права доступа на файлы и каталоги 
g) Жёсткая ссылка ( Ctrl-x l ) позволяет создать жёсткую ссылку к текущему (или выделенному) файлу1 . 
h) Символическая ссылка ( Ctrl-x s ) — позволяет создать символическую ссылку к текущему файлу . 
i) Владелец группы ( Ctrl-x o ) позволяет задать владельца и имя группы для одного или нескольких файлов или каталогов. 
j) Права (расширенные)  позволяет изменить права доступа и владения для одного или нескольких файлов или каталогов. 
k) Переименование ( F6 ) позволяет переименовать один или несколько файлов или каталогов.
l) Создание каталога ( F7 ) позволяет создать каталог. 
m) Удалить ( F8 ) позволяет удалить один или несколько файлов или каталогов. 
n) Выход ( F10 )  завершает работу mc. 

5 Опишите структура меню Команда mc, дайте характеристику командам
Ответ: Ответ: Меню Команда mc представляет собой следующую конструкцию:

Где подпункты меню
a) Дерево каталогов отображает структуру каталогов системы.
b) Поиск файла выполняет поиск файлов по заданным параметрам.  
c) Переставить панели меняет местами левую и правую панели. 
d) Сравнить каталоги ( Ctrl-x d ) сравнивает содержимое двух каталогов. 
e) Размеры каталогов отображает размер и время изменения каталога (по умол- чанию в mc размер каталога корректно не отображается).
f) История командной строки выводит на экран список ранее выполненных в оболочке команд. 
g) Каталоги быстрого доступа ( Ctrl-\ ) при вызове выполняется быстрая смена текущего каталога на один из заданного списка. 
h) Восстановление файлов позволяет восстановить файлы на файловых систе- мах ext2 и ext3. 
i) Редактировать файл расширений позволяет задать с помощью определённого синтаксиса действия при запуске файлов с определённым расширением (напри- мер, какое программного обеспечение запускать для открытия или редактирова- ния файлов с расширением .c или .cpp). 
j) Редактировать файл меню позволяет отредактировать контекстное меню поль- зователя, вызываемое по клавише F2 . 
k) Редактировать файл расцветки имён позволяет подобрать оптимальную для пользователя расцветку имён файлов в зависимости от их типа.

6. Опишите структура меню Настройки mc, дайте характеристику командам
Ответ: Меню Настройки mc представляет собой следующую конструкцию:

Где подпункты меню
a) Конфигурация позволяет скорректировать настройки работы с панелями. 
b) Внешний вид и Настройки панелей определяет элементы, отображаемые при вызове mc, а также цветовое выделение. 
c) Биты символов задаёт формат обработки информации локальным термина- лом. 
d) Подтверждение позволяет установить или убрать вывод окна с запросом подтверждения действий при операциях удаления и перезаписи файлов, а также при выходе из программы.
e) Распознание клавиш диалоговое окно используется для тестирования функциональных клавиш, клавиш управления курсором и прочее.
f) Виртуальные ФС настройки виртуальной файловой системы: тайм-аут, пароль и прочее.

7. Назовите и дайте характеристику встроенным командам mc.
Ответ: В командную оболочку mc встроены стандартные команды. Вот некоторые из них.
a) F1 Вызов контекстно-зависимой подсказки.
b) F2 Вызов пользовательского меню с возможностью создания and/or.
c) F3 Просмотр содержимого файла, на который указывает подсветка в активной панели.
d) F4 Вызов встроенного в mc редактора для изменения содержания файла, на который указывает подсветка в активной панели.
d) F5 Копирование одного или нескольких файлов, отмеченных в первой (активной) панели, в каталог, отображаемый на второй панели.
e) F6 Перенос одного или нескольких файлов, отмеченных в первой панели, в каталог, отображаемый на второй панели.
f) F7 Создание подкаталога в каталоге, отображаемом в активной панели.
g) F8 Удаление одного или нескольких файлов, отмеченных в первой панели файлов.
h) Вызов меню mc.
i) F10 Выход из mc.

8 Назовите и дайте характеристику командам встроенного редактора mc.
Ответ: В редактор mc встроено немало команд. Вот некоторые из них.
a) Ctrl+y удалить строку.
b) Ctrl+u отмена последней операции. 
c) Ins вставка/замена.
d)F7 поиск.
d)Shift+F7 повтор последней операции поиска.
e) F4 замена файла.
f) F3 первое нажатие начало выделения, второе это окончание выделения.
g) F5 копировать выделенный фрагмент F6 переместить выделенный фрагмент.
h) F8 удалить выделенный фрагмент.
i) F2 записать изменения в файл.
j) F10 выйти из редактора.

9. Дайте характеристику средствам mc, которые позволяют создавать меню, определяемые пользователем.
Ответ: Один из четырех форматов списка в Midnight Commander -Пользовательский определённый самим пользователем позволяет ему редактировать меню любого из двух списков. А меню пользователя – это меню, состоящее из команд, определенных пользователем. При вызове меню используется файл ~/.mc.menu. Если такого файла нет, то по умолчанию используется системный файл меню /usr/lib/mc/mc.menu. Все строки в этих файлах  , начинающиеся с пробела или табуляции, являются командами, которые выполняются при выборе записи.

10. Дайте характеристику средствам mc, которые позволяют выполнять действия, определяемые пользователем, над текущим файлом
Ответ: Когда мы выделяем файл не являющегося исполняемым, Midnight Commander сравнивает расширение выбранного файла с расширениями, прописанными в «файле расширений» ~/mc.ext. Если в файле расширений найдется подраздел, задающий процедуры обработки файлов с данным расширением, то обработка файла производится в соответствии с заданными в этом подразделе командами и файлами:
a) файл помощи для MC. /usr/lib/mc.hlp
b) файл расширений, используемый по умолчанию. /usr/lib/mc/mc.ext
c)  файл расширений, конфигурации редактора. $HOME/.mc.ext
d) системный инициализационный файл. /usr/lib/mc/mc.ini
e) фаил который содержит основные установки. /usr/lib/mc/mc.lib
g) инициализационный файл пользователя. Если он существует, то системный файл mc.ini игнорируется. $HOME/.mc.ini
h) этот файл содержит подсказки, отображаемые в нижней части экрана. /usr/lib/mc/mc.hint
i) системный файл меню MC, используемый по умолчанию. /usr/lib/mc/mc.menu
j) файл меню пользователя. Если он существует, то системный файл меню игнорируется. $HOME/.mc.menu
k) инициализационный файл пользователя. Если он существует, то системный файл mc.ini игнорируется. $HOME/.mc.tree
