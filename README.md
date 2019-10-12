Скрипт по умолчанию сканирует диапазоны IP-адресов встроенного плейлиста Ростелеком (Новосибирск) и создаёт 3 файла:
SimpleTV - плейлист в кодировке ANSI. Подходит для просмотра в плеере SimpleTV и других плеерах, поддерживающих кодировку ANSI.
VLC - плейлист в кодировке UTF-8. Подходит для просмотра в плеере VLC и на телевизоре Smart TV, не поддерживающих кодировку ANSI.
Статистика - просмотр статистики серверов.



### curl.exe - консольная утилита скачивания и закачивания файлов по сети. Сайт проекта http://curl.haxx.se/.
### gsar.exe - консольная утилита поиска и замены текста в текстовых файлах. Сайт проекта http://gnuwin32.sourceforge.net/packages/gsar.htm
### sleep.exe - консольная утилита задержки ожидания перед выполнением определённых команд. Сайт компании http://microsoft.com/.
### tcping.exe - консольная утилита сканера портов. Сайт проекта http://www.elifulkerson.com/projects/tcping.php.
### vnc.exe - консольная утилита сканера портов. Бывшый сайт проекта http://heapoverflow.com/.
### win_iconv.exe - консольная утилита перекодировки текстовых файлов. Сайт проекта http://code.google.com/p/win-iconv/.

Все эти утилиты необходимы для работы скрипта.
Если во время сканирования появляются сообщения "Не удаётся найти файл curl.exe, gsar.exe, sleep.exe, tcping.exe, vnc.exe или win_iconv.exe", то попробуйте переместить эти файлы в папку C:\Windows\System32\ и запустить скрипт от имени Администратора.



У скрипта есть расширенные настройки для экспертов. Чтобы их изменить, откройте скрипт через блокнот или через любой текстовый редактор и измените необходимые параметры.
В расширенных настройках можно использовать свой плейлист, изменять диапазоны сканирования IP-адресов, искать свободные сервера, проверять вещание каналов на сервере, искать каналы на прокси-сервере, закачивать плейлисты на FTP и многое другое...



Чтобы использовать функцию "Многопоточное сканирование" нужно скачать сканер vnc.exe, поместить его в папку со скриптом и в настройках скрипта включить функцию "Многопоточное сканирование".
Большинство антивирусов распознают утилиту vnc.exe как HackTool из-за того, что её часто используют взломщики для получения доступа к удалённому рабочему столу.
