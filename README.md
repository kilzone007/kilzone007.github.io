# kilzone007.github.io

# Отчет по лабораторным работам
# студент группы [ИДБ-16-05](https://github.com/stankin/design-2018/wiki/list-idb-16-05) Тараненко А.Ф.

## Лабораторная работа №1

### Создание IDEF0-диаграммы "Сборка телефона" в RAMUS (программное средство разработки структурно-функциональных моделей)

* IDEF0-диаграмма в развернутом виде:
![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/RAMUS(A0).png)
**Мастер при помощи инструментов собирает из материалов телефон по схеме сборки**

### Создание диаграммы классов и диаграммы прецедентов "Сборка телефона" в PLANTUML (программное средство автоматической генерации UML-диаграмм)
**Сборка телефона**
* [Текст](https://github.com/kilzone007/kilzone007.github.io/blob/master/PlantUML(text).txt) и [Картинка](https://github.com/kilzone007/kilzone007.github.io/blob/master/PlantUML.png) диаграммы классов

![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/PlantUML.png)

**Мастер является человеком, который использует инструменты. Мастер умеет собирать телефоны в соответствии со схемой сборки.**

* [Текст](https://github.com/kilzone007/kilzone007.github.io/blob/master/PlantUML2(text).txt) и [Картинка](https://github.com/kilzone007/kilzone007.github.io/blob/master/PlantUML2.png) диаграммы прецедентов

![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/PlantUML2.png)

## Лабораторная 2

### Определение надсистемы (среды функционирования) 

* IDEF0-диаграмма (блок А0): 

![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba2(photo1).jpg)

* IDEF0-диаграмма (блоки A1, A2, A3, A4):

![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba2(photo2).jpg)

* DFD-диаграмма "Подготовить такст к публикации" (блок A3-03):

![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba2(photo3).jpg)

* [Диаграмма в формате .rsf](https://github.com/kilzone007/kilzone007.github.io/blob/master/LABA2.rsf)

### Описание участников автоматизируемой деятельности

* [Текст](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba2(text).txt) и [Рисунок](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba2(UML).png) диаграммы прецедентов 

![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba2(UML).png)

## Лабораторная 3

### Описание хранилищ данных

* DFD-диаграмма "Разместить статью в издании" (блок A4-03)

![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba3(DFD).jpg)

* [Диаграмма формате .rsf](https://github.com/kilzone007/kilzone007.github.io/blob/master/LABA3.rsf)

### Описание взаимодействия участников автоматизируемой деятельности

* [Текст](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba3(text1).txt) и [рисунок](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba3(UML1).png) диаграммы последовательности

![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba3(UML1).png)

### Описание участников автоматизируемой деятельности

* [Текст](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba3(text2).txt) и [Рисунок](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba3(UML2).png) диаграммы классов

![none](https://github.com/kilzone007/kilzone007.github.io/blob/master/Laba3(UML2).png)

## Лабораторная 4

## Лабораторная 5

## Лабораторная 6

## Лабораторная 7

# Отчет по семинарам

## Семинар 1
1. Плохая система: рюкзак. 
Является инструментом, для достижения цели (перенос вещей из пункта А в пункт Б), но сам по себе не имеет цели. 

2. Пример "плохого проекта" неавтоматизируемой системы: подготовиться к экзаменам.

* Конкретность: не известно к какому экзамену необходимо готовиться
* Измеримость: не понятен критерий оценки выполнения задачи.
* Достижимость: в отсутствии временных рамок и критериев оценки невозможно достичь поставленную цель.
* Значимость: имеет значимость только при выполнении цели, но невозможно ее оценить в связи с отсутствием конкретных параметров.
* Ограниченность во времени: не указаны сроки выполнения

Пример "плохого проекта" неавтоматизируемой системы: подготовиться к экзаменам: подготовиться к экзамену по математике, чтобы получить больше 40 баллов, который пройдет 28 декабря.

* Конкретность: известно к какому экзамену необходимо подготовиться.
* Измеримость: указана оценка, которая измеряется в баллах.
* Достижимость: цель достижима и может быть проверена на соответствие поставленной цели.
* Значимость: если экзамен будет сдан на оценку ниже 40, то студент лишится стипендии.
* Ограниченность во времени: присутствует (до 28 декабря).

3. Пример "плохого проекта" автоматизируемой системы:
Автоматизация расчета заработной платы.

* Конкретность: не известно чью заработную плату необходимо рассчитать и на основании чего.
* Измеримость: отсутствуют критерии расчета, а значит измеримость не обеспечивается
* Достижимость: не достижима, в силу отсутствия корректных требований и ограничений.
* Значимость: уменьшение ручных расчетов, снижение ошибок.
* Ограниченность во времени: отсутствует.

Пример "хорошего проекта" автоматизируемой системы: реализовать систему автоматического расчета заработной платы сотрудников на основе данных СКУД до декабря.

* Конкретность: указано что нужно сделать.
* Измеримость: измерима.
* Достижимость: достижима.
* Значимость: упрощение работы сотрудникам.
* Ограниченность во времени: есть

## Семинар 2
1. Плохая система:
* Система - Рюкзак
* Подсистема - Органайзер рюкзака
* Надсистема - Пешеход

2. Система с целью:
* Система - Расчет заработной платы
* Подсистема - Система контроля управления доступом
* Надсистема - Бухгалтерия

## Семинар 3
Задание 1:
Пример цикла Деминга: 
Цель: создание сайта для магазина

* Plan (планирование): в соответствие с требованиями заказчика по созданию сайта, планируется список работ и план выполнения.
* Do (выполнение): выполняются все этапы плана и реализуется сайт.
* Check (проверка): оценка юзабилити сайта, а также его надежности.
* Update (улучшения): на основание полученных данных внесение исправлений и оптимизация. 

Задание 2:
* Муда - использование света в хорошо освещенном помещение. Включение или выключение света не меняет освещенность помещения, при этом на его работу тратится энергия (деньги). Например днем на остекленном балконе. 
* Мура - на конвейерном производстве, когда одна технологическая операция занимает значительно больше времени, чем предшествующая. В итоге возникает простой оборудования на предыдущей операции. Получается эффект бутылочного горлышка. Возможное решение - разбиение одной операции на несколько, использование большего количество оборудования, параллельное выполнение одной операции несколькими линиями. 
* Мури - в следствии задержки поставок материалов и невозможности переноса сроков повышается нагрузка на оборудование и людей (работа в несколько смен, без перерывов и т.д.). Другой пример из истории - "пятилетку за три года".

## Семинар 4

1. **Антипаттерны разработки** - Таинственный код (Cryptic code). 
Подразумевает использование аббревиатур вместо мнемоничных имён. Приводит к нечитаемости кода. В случае ухода автора этого кода из проекта/компаний такой код может стать "головоломкой" для остальных. 

2. **Архитектурные антипаттерны** - Затычка на ввод данных (Input kludge).
Забывчивость в спецификации и выполнении поддержки возможного неверного ввода.
Приводит к возникновению ошибок и остановкам программы. Антипаттерн устраняется продуманным алгоритмом проверки (валидации) пользовательского ввода.

3. **Организационные антипаттерны** - Привязка к поставщику (Vendor lock-in). 
Жёсткая привязка к поставщику. Опасный подход, который может приводить к необоснованному росту цены изделий/услуг поставщика, делает собственную организацию более зависимой от сторонних факторов. Пример: Sukhoi SuperJet - большая часть компонентов поставляется ограниченным числом зарубежными компаниями, использование сторонних компонентов не предусматривается -> санкции привели к перебоям с поставками -> снижение эффективности использования этих самолетов (долгий простой на ремонте) -> отказ от новых заказов. 

4. **Антипаттерны среды** - Увлечение модными словами (Buzzword Mania)
Неуместное и нецелевое использование модных слов, которое может вводить окружающих в заблуждение. Поэтому важно вести беседу на понятном и однозначно интерпретируемом языке, чтобы избегать недопониманий и ущерба в следствии него. 
