## Запуск сервера
#### Через терминал
php -S localhost:9093 -t public_html/
#### Через  openserver
Нужно настроить папку домена public_html/
## Настройка файла конфигурации и дамб базы данных
####  Конфигурация config.php
Зайти в папку **app/core** и вставить конфиги базы данных из **config-ex.php** в **сonfig.php** изменив настройки подключения к mysql серверу, при этом имя базы данных нужно **обязательно** оставить таким же, для корректной работы.
####  Дамп базы данных
В папке **migrations** находится дамп базы данных mysql, импортировать данную базу к себе любым способом.

