# Проект с логикой управления лифтами

## Оглавление  
<a id = '0'></a>
<a href ="#1">1. Описание проекта</a><br>
<a href ="#2">2. Что сделаем?</a><br>
<a href ="#3">3. Краткая информация о задаче</a><br>
<a href ="#4">4. Этапы работы над проектом</a><br>
<a href ="#5">5. Результат</a><br>
<a href ="#6">6. Выводы</a><br>

### Описание проекта    
<a id = '1'></a>
Разработчики пишут программы для веб-приложений, игр, аналитики и управления ракетами. Но: в простых повседневных вещах тоже нужен код, и его тоже должен кто-то писать. Сегодня напишем один из таких полезных проектов — систему управления лифтами в 11-этажном доме и визуализацию для этой системы

:arrow_up:<a href ="#0">к оглавлению</a>


### Что сделаем?    
<a id = '2'></a>
Для начала создадим простую систему:

- здание в 11 этажей;
- грузовой и обычный лифты;
- каждый лифт вызывается по своей кнопке.

### Краткая информация о задаче
<a id = '3'></a>
Для создания элементов нашего лифтового узла используем объектно-ориентированное программирование: сделаем классы для лифтов, кнопок и этажей и у каждого класса настроим свои атрибуты и методы, например передвижение на нужный этаж. А потом всё это свяжем одной функцией для запуска.

Для визуализации подключим библиотеку pygame. Она используется для написания несложных игр на Python и идеально подойдёт для интерактивной визуализации передвижения двух лифтов. В каждый объект-элемент мы добавим изображение, чтобы видеть работу лестничного узла.

:arrow_up:<a href ="#0">к оглавлению</a>


### Этапы работы над проектом  
<a id = '4'></a>
1. Устанавливаем библиотеку для визуализации.
2. Готовим настройки визуализации.
3. Создаём кнопки вызова.
4. Создаём этажи.
5. Создаём лифты.
6. Проверяем, что получается.
7. Создаём общий класс для системы.
8. Устанавливаем нужный этаж в лифте.
9. Создаём основную логику приложения.
10. Проверка работоспособности и формирование выводов.

:arrow_up:<a href ="#0">к оглавлению</a>


### Результат:  
<a id = '5'></a>
У нас есть хорошая работающая программа, но можно сделать её реальнее:

- сделать так, чтобы лифты не меняли направление после каждого нажатия, а ехали до того этажа, где их вызвали;
- разделить кнопки вызова на «вверх» и «вниз»;
- придумать логику, чтобы лифт не останавливался на этажах с нажатой кнопкой «вниз», если едет вверх;
- отключить лифт на одном из этажей, потому что там неисправны двери.

:arrow_up:<a href ="#0">к оглавлению</a>


### Выводы:  
<a id = '6'></a>
Над улучшением продумаем и напишем в следующий раз. Сейчас у нас есть хорошая основа, потому что вся программа поделена на классы — и внутри их можно добавлять новые функции или изменять старые.

Буду рад зведочке сверху ⭐️⭐️⭐️

:arrow_up:<a href ="#0">к оглавлению</a>