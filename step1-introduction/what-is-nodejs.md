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

## обзор

Node.js — программная платформа, основанная на

https://mcgill-csus.github.io/student_projects/Submission2.pdf

- движке V8, выполняющем JS код
- libUV (event loop реализация для NodeJS.  Отличное видео ["What the heck is the event loop anyway?"](https://www.youtube.com/watch?v=8aGhZQkoFbQ) для понимания концепции event loop)
- API на C++ для организации взаимодействия с программами OS (чтение/запись файлов, операции с базами данных, сетью и др.)

- Node.js API
  These are written in JavaScript and directly exposed to outer world to interact with Node.js internal components. Node.js Binding – These are Core API, which bind the JavaScript with C / C++ libraries.
- C/C++ Add-ons
  You can also develop your Node.js Add-ons using C/C++ to work with Node.js.
- V8
  It is Google’s open source JavaScript engine, written in C++. Actually, it is a JavaScript VM which compile the JavaScript code into native machine code instead interpretation. It is the fastest JIT (Just-In-Time) compiler for JavaScript.
- Libuv
  It is a multi-platform support C++ library which is responsible for handling thread pool, event loop and async I/O operations in Node.js. In Node.js, blocking I/O operations are delegated to Libuv modules which has a fixed size C++ thread pool to handle these operations. When these operations are completed, they are notified to Event loop.
- C-ares
  It is a C library for handling async DNS request, name resolves and multiple DNS queries in parallel.
- http_parser
  It is a C library for parsing HTTP request and response.
- OpenSSL
  It is a C library for the implementation of Secure Sockets Layer (SSL v2/v3) and Transport Layer Security (TLS v1) protocols. It also provides all the necessary cryptography methods like hash, cipher, decipher, sign and verify etc.
- Zlib
  It is a C library for data compression and decompression.


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