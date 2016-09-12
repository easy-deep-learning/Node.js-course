# Введение в Node.js


Видеообзор [Node.js Explained](https://www.youtube.com/embed/L0pjVcIsU6A).



## история

Javascript изначально [был создан](https://en.wikipedia.org/wiki/JavaScript#History) для разработки динамичных web-страниц в 1995 компанией Netscape (браузер  Mosaic Netscape). В том же году компания выпустила серверную версию Javascript для своего веб-сервера [Netscape Enterprise Server](https://en.wikipedia.org/wiki/Netscape_Enterprise_Server). Первоначально серверный js не получил большого распостранения, но с середины 2000-х началась активная разработка [серверных реализаций](https://en.wikipedia.org/wiki/Comparison_of_server-side_JavaScript_solutions), наиболее популярная из которых [Node.js](https://en.wikipedia.org/wiki/Node.js).

Платформа Node.js была написана в 2009 году разработчиком [Ryan Dahl](https://en.wikipedia.org/wiki/Node.js#History). Главная идея заключалась в реализации неблокирующих операций ввода-вывода (Input/Output).

Цитируя создателя ([источник](https://www.youtube.com/watch?v=Fc26auhSLqM#t=112)) :

> Оказывается, многие фреймворки были спроектированы с предположением, что ответ на запрос приходит мгновенно. [...] Отправляя запрос вы тут же получаете ответ.
>
> Платформа Node.js родилась как ответ на вопрос — "как можно выполнять несколько дел одновременно?". [...] Что, если сделать все операции ввода-вывода неблокирующими?

[Первая презентация Node.js на JSConf 2009](https://www.youtube.com/watch?v=ztspvPYybIY) (примеры блокирующих операций, способы решения, цель ). [jsconf.pdf](http://s3.amazonaws.com/four.livejournal/20091117/jsconf.pdf)

[Первый](https://github.com/nodejs/node/commit/9d7895c567e8f38abfff35da1b6d6d6a0a06f9aa) коммит в репозитории [nodejs/node](nodejs/node).



## обзор

Node.js — программная платформа, она состоит из двух частей: Ядро и Модули.

#### Ядро

https://github.com/nodejs/node/tree/master/src

#### Модули

https://github.com/nodejs/node/tree/master/deps

- **Движок** выполнения javascript кода: Google [V8](https://en.wikipedia.org/wiki/V8_(JavaScript_engine))

- **event loop + асинхронные операции I/O**: [libUV](https://en.wikipedia.org/wiki/Libuv) — event loop + асинхронные операции I/O.

  До 2012 (до версии nodejs `0.9.0`) года для этой цели были библиотеки `Libio` и `Libev`.

- **API на C++** для организации взаимодействия с программами OS (чтение/запись файлов, операции с базами данных, сетью и др.)

- **C/C++ Add-ons**
  You can also develop your Node.js Add-ons using C/C++ to work with Node.js.

- **C-ares**
  It is a C library for handling async DNS request, name resolves and multiple DNS queries in parallel.

- **http_parser**
  It is a C library for parsing HTTP request and response.

- **OpenSSL**
  It is a C library for the implementation of Secure Sockets Layer (SSL v2/v3) and Transport Layer Security (TLS v1) protocols. It also provides all the necessary cryptography methods like hash, cipher, decipher, sign and verify etc.

- **Zlib**
  It is a C library for data compression and decompression.



Доп чтение:

- Отличное видео ["What the heck is the event loop anyway?"](https://www.youtube.com/watch?v=8aGhZQkoFbQ) для понимания концепции event loop
- [An Inside Look at the Architecture of NodeJS]( https://mcgill-csus.github.io/student_projects/Submission2.pdf)



## экосистема

- Документация: https://nodejs.org/en/docs/
- Репозиторий: https://github.com/nodejs/node
- Модули (npm-пакеты): https://www.npmjs.com
- Курсы TODO




## запуск программы в консоли

Node CLI https://nodejs.org/api/cli.html



## отладка

#### логирование

- https://nodejs.org/api/console.html
- https://github.com/winstonjs/winston#readme

#### дебаг

- https://nodejs.org/api/debugger.html
- https://github.com/visionmedia/debug