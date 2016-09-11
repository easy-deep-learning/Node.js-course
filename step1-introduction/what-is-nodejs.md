# Введение в Node.js


Видеообзор [Node.js Explained](https://www.youtube.com/embed/L0pjVcIsU6A).

## история

Javascript изначально [был создан](https://en.wikipedia.org/wiki/JavaScript#History) для разработки динамичных web-страниц в 1995 компанией Netscape (браузер  Mosaic Netscape). В том же году компания выпустила серверную версию Javascript для своего веб-сервера [Netscape Enterprise Server](https://en.wikipedia.org/wiki/Netscape_Enterprise_Server). Первоначально серверный js не получил большого распостранения, но с середины 2000-х началась активная разработка [серверных реализаций](https://en.wikipedia.org/wiki/Comparison_of_server-side_JavaScript_solutions), наиболее популярная из которых [Node.js](https://en.wikipedia.org/wiki/Node.js).

Платформа Node.js была написана в 2009 году разработчиком [Ryan Dahl](https://en.wikipedia.org/wiki/Node.js#History). Главная идея заключалась в реализации неблокирующих операций ввода-вывода (Input/Output).

Цитируя создателя ([источник](https://www.youtube.com/watch?v=Fc26auhSLqM#t=112)) :

> Оказывается, многие фреймворки были спроектированы с предположением, что ответ на запрос приходит мгновенно. [...] Отправляя запрос вы тут же получаете ответ.
>
> Платформа Node.js родилась как ответ на вопрос — "как можно выполнять несколько дел одновременно?". [...] Что, если сделать все операции ввода-вывода неблокирующими?

[Первая презентация Node.js на JSConf 2009](https://www.youtube.com/watch?v=ztspvPYybIY) (примеры блокирующих операций, способы решения, цель ).

## обзор

Node.js — программная платформа, основанная на 

- движке V8, выполняющем JS код
- libUV (event loop реализация для NodeJS.  Отличное видео ["What the heck is the event loop anyway?"](https://www.youtube.com/watch?v=8aGhZQkoFbQ) для понимания концепции event loop)
- API на C++ для организации взаимодействия с программами OS (чтение/запись файлов, операции с базами данных, сетью и др.)



## экосистема

- Документация
- Репозиторий
- Модули (npm-пакеты)
- Курсы




## запуск программы в консоли

Node CLI



## отладка

Логирование

Дебаг