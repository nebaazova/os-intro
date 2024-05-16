---
## Front matter
title: "Отчёт по прохождению внешнего курса"
subtitle: "(2 блок: Работа на сервере)"
author: "Баазова Нина Эдгаровна"

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

Ознакомиться с функционалом операционной системы Linux.

# Задание

Посмотреть видео и на основе полученной информации пройти тестовые задания.

# Выполнение 2 этапа внешних курсов на stepik

Задание №1: удаленный сервер - это компьютер, находящийся в дата-центре, к которому можно получить удаленный доступ через сеть Интернет. Удаленный сервер обычно используется для размещения веб-сайтов, приложений, баз данных и других сервисов, которые необходимы для функционирования сайта или бизнес-процессов компании. Пользователи могут получить доступ к удаленному серверу с помощью протоколов удаленного доступа, таких как RDP, VNC или SSH 

![Задание №1](image/ST2_1.png){#fig:001 width=70%}

Задание №2: только id_rsa.pub, так как он является открытым 

![Задание №2](image/ST2_2.png){#fig:002 width=70%}

Задание №3: -r = рекурсивно копировать целые каталоги. Обратите внимание, что scp следует по символическим ссылкам, встречающимся при обходе дерева 

![Задание №3](image/ST2_3.png){#fig:003 width=70%}

Задание №4: надо проверить интернет соединение на предмет того, что устройство не может соединиться с сервером, затем проверяем то, знает ли оно вообще о существовании такой программы

![Задание №4](image/ST2_4.png){#fig:004 width=70%}

Задание №5: FileZilla — свободный многоязычный проект, посвящённый приложениям для FTP. Включает в себя отдельное приложение «FileZilla Client» (являющееся FTP- клиентом), и «FileZilla Server». Приложения публикуются с открытым исходным кодом для Windows, macOS и Linux. Клиент поддерживает FTP, SFTP, и FTPS (FTP через SSL/TLS) и имеет настраиваемый интерфейс с поддержкой смены тем оформления 

![Задание №5](image/ST2_5.png){#fig:005 width=70%}

Задание №6: на скрине всё видно (рис. [-@fig:006])

![Задание №6](image/ST2_6.png){#fig:006 width=70%}

Задание №7: на скрине всё видно (рис. [-@fig:007])

![Задание №7](image/ST2_7.png){#fig:007 width=70%}

Задание №8: установила FastQC команду *sudo apt-get install fastqc* 

![Задание №8](image/ST2_8.png){#fig:008 width=70%}

Задание №9: -align Do full multiple alignment. - подходящая команда 

![Задание №9](image/ST2_13.png){#fig:013 width=70%}

Задание №10: комбинация Ctrl+С - завершает процесс. Комбинация Ctrl+Z - приостанавливает процесс 

![Задание №10](image/ST2_14.png){#fig:014 width=70%}

Задание №11: на скрине всё видно 

![Задание №11](image/ST2_15.png){#fig:015 width=70%}

Задание №12: если сигнал не перехватывается процессом, процесс уничтожается. Следовательно, это используется для изящного завершения процесса. Команда «kill -9» отправляет сигнал уничтожения для немедленного завершения любого процесса, если он присоединен к PID или имени процесса . Это принудительный способ убить/завершить набор процессов 

![Задание №12](image/ST2_16.png){#fig:016 width=70%}

Задание №13: команда kill шлёт сигнал о завершении процесса. Но программа обрабатывает сигналы только когда она исполняется, пока она остановлена она не может обработать сигнал и приступит к его обработке только после продолжения работы 

![Задание №13](image/ST2_17.png){#fig:017 width=70%}

Задание №14: запущенная программа потребляет ресурсы CPU, а остановленная нет 

![Задание №14](image/ST2_18.png){#fig:018 width=70%}

Задание №15: приостановленное приложение не выполняет новых действий, поэтому не занимает вычислительные ресурсы компьютера (CPU 0%). При этом, в оперативной памяти оно сохранится, поэтому оно будет занимать столько же оперативной памяти, сколько до постановки на паузу 

![Задание №15](image/ST2_19.png){#fig:019 width=70%}

Задание №16: на скрине всё видно 

![Задание №16](image/ST2_20.png){#fig:020 width=70%}

Задание №17:
- bowtie2 поддерживает многопоточность с помощью флага --threads, который позволяет указывать количество потоков, которые будут использоваться для выравнивания
- bowtie2-build - это программа для создания индексных файлов для bowtie2, и она не поддерживает многопоточность

![Задание №17](image/ST2_22.png){#fig:022 width=70%}

Задание №18: скачиваем необхожимые файлы и далее выполняем задание
Ответ:

```
306174 reads; of these:
  306174 (100.00%) were unpaired; of these:
    11 (0.00%) aligned 0 times
    305580 (99.81%) aligned exactly 1 time
    583 (0.19%) aligned >1 times
100.00% overall alignment rate
```


![Задание №18](image/ST2_22.png){#fig:024 width=70%}

Задание №19: на скрине всё видно 

![Задание №19](image/ST2_25.png){#fig:025 width=70%}

Задание №20: exit завершает работу tmux 

![Задание №20](image/ST2_26.png){#fig:026 width=70%}

Задание №21: мы заходили на сервер с терминала, который закрыли, а tmux будет продолжать свою работу на сервере 

![Задание №21](image/ST2_27.png){#fig:027 width=70%}

Задание №22: будет предупреждение о том, что работа завершится. Запущенный процесс
во вкладке, при её закрытии, пропадёт 

![Задание №22](image/ST2_28.png){#fig:028 width=70%}

Задание №23: изучила справку по tmux 

![Задание №23](image/ST2_30.png){#fig:030 width=70%}

Задание №24: на скрине всё видно 

![Задание №24](image/ST2_31.png){#fig:031 width=70%}

# Выводы

В ходе выполнения 2 этапа внешних курсов на stepik я освоила linux, terminal, запуск приложений, многопоточные приложения, а также исвоила tmux.

# Список литературы

1. Курс на stepik. Работа на сервере [Электронный ресурс] URL: https://stepik.org/course/73/syllabus?id=1098930
