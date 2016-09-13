# Установка софта

- Node.js
- Webstorm
- GIT



## Установка Node.js

Переходим по ссылке: https://nodejs.org/en/download/current/  
Выбираем нужную ОС и формат:  
![Node.js download page](img/setup_nodejs_win_001.png "Node.js download page")  

### Установка под Windows

Нажимаем на 32 или 64 битный установщик (.msi) в зависимости от вашей системы. После скачивания файла установщика запускаем его.  
Нажимаем Next:  
![Welcome to setup wizard](img/setup_nodejs_win_002.png "Welcome to setup wizard")  
Отмечаем что согласны с условиями лицензии:  
![End-User License Agreement](img/setup_nodejs_win_003.png "End-User License Agreement")  
Выбираем путь куда буде установлен Node.js:  
![Node.js install destination folder](img/setup_nodejs_win_004.png "Node.js install destination folder")  
Настройки оставляем по умолчанию:  
![Custom setup](img/setup_nodejs_win_005.png "Custom setup")  
Нажимаем Install:  
![Ready to install](img/setup_nodejs_win_006.png "Ready to install")  
Ждем пока Node.js установиться о чем нам сообщит следующие окно:
![Completed install](img/setup_nodejs_win_007.png "Completed install")  
Нажимаем Finish.  
Установка завершенна. Поздравляю!  
Проверим или все установилось правильно. Запускаем окно командной строки (Command prompt). Для этого зажав кнопку WIN нажимаем кнопку R. В открывшемся окне пишем ***cmd*** и нажимаем OK.  
![Run window](img/setup_nodejs_win_008.png "Run window")  
В открывшемся окне пишем команду ***node –v*** нажимаем Enter. На экране должна отобразиться версия установленного Node.js:  
![Command prompt](img/setup_nodejs_win_009.png "Command prompt")

## Установка Git

Переходим по ссылке: https://git-scm.com/downloads
Выбираем нужную ОС и формат:
![Git download page](img/setup_git_win_001.png "Git download page")

### Установка под Windows

Читаем условия лицензии, и нажимаем Next:
![GNU General Public License](img/setup_git_win_002.png "GNU General Public License")
Отмечаем все пункты в настройках (создание иконки на рабочем столе, интеграция с проводником, установка программы по умолчанию для файлов с расширением .git, .sh), нажимаем Next:
![Select components](img/setup_git_win_003.png "Select components")
Оставляем  настройку по умолчанию (команда git будет доступна в окне командной строки), нажимаем Next:
![git PATH setup](img/setup_git_win_004.png "git PATH setup")
Оставляем настройку по умолчанию (настройка символа конца строки при checkout и commit), нажимаем Next:
![setup line ending conversion](img/setup_git_win_005.png "setup line ending conversion")
Оставляем настройку по умолчанию (настройка эмулятора терминального  окна), нажимаем Next:
![configure terminal emulator](img/setup_git_win_006.png "configure terminal emulator")
Оставляем настройку по умолчанию (дополнительные настройки кэширования и доступа), нажимаем Install:
![extra options](img/setup_git_win_007.png "extra options")
Ждем пока установка завершится. Отмечаем первую опцию (запуск терминала Git Bash), нажимаем: Finish:
![complete installation](img/setup_git_win_008.png "complete installation")
Должно запуститься терминальное окно. Набираем команду ***git --version***. Если все прошло успешно, то отобразится установленная версия Git:
![check git version in teminal](img/setup_git_win_009.png "check git version in teminal")


## Установка Webstorm

IDEA Webstorm — IDE для веб-разработки, включает в себя поддержку HTML, CSS, JS (клиентского и серверного NodeJS), GIT.

Перейти по ссылке: https://www.jetbrains.com/webstorm/download/
Выбираем нужную ОС:
![download WebStorm](img/setup_ws_win_001.png "download WebStorm")

### Установка под Windows

Запускаем установку. Нажимаем Next:  
![welcome to setup wizard](img/setup_ws_win_002.png "welcome to setup wizard")  
Выбираем путь куда буде установлен Webstorm:  
![choose installation location](img/setup_ws_win_003.png "choose installation location")  
Выбираем типы файлов, которые по умолчанию будут открываться в Webstorm. Нажимаем Next:  
![installation options](img/setup_ws_win_004.png "installation options")  
Оставляем название папки в стартовом меню по умолчанию.  Нажимаем Install:  
![start menu folder](img/setup_ws_win_005.png "start menu folder")  
Запускаем Webstorm после установки для настройки. Нажимаем Finish:
![completing setup wizard](img/setup_ws_win_006.png "completing setup wizard")  
При первом запуске программа попросит указать файл с конфигурацией. Если такого нет то отмечаем последний пункт:  
![import configuration](img/setup_ws_win_007.png "import configuration")  
Читаем и принимаем политику конфиденциальности:  
![privacy policy](img/setup_ws_win_008.png "privacy policy")  
Отмечаем что будем использовать пробный 30 дневной период. Нажимаем Evaluate::  
![license activation](img/setup_ws_win_009.png "license activation")  
Принимаем условия лицензии. Нажимаем Accept:  
![license agreement](img/setup_ws_win_010.png "license agreement")  
В низу окна нажимаем Configure и выбираем первый пункт меню - Settings:  
![configure settings](img/setup_ws_win_011.png "configure settings")  
Переходим к настройке.

### Настройка

1. Выбор версии языка javascript:

   1. Preferencies > Languages & Frameworks > JavaScript
   2. установить значение: **ES 2015+ (ECMAScript 6)**

![javascript language version](img/setup_ws_win_012.png "javascript language version")  


2. Настройка github
   TODO
