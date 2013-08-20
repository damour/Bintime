Установка и настройка phpcodesniffer:
---------------------------------------------------------------

sudo pear install PHP_CodeSniffer

cd /usr/share/php/PHP/CodeSniffer/Standards

sudo git clone https://github.com/damour/Bintime.git

sudo phpcs --config-set tab_width 4

sudo phpcs --config-set default_standard Bintime

Использование: 
------------------------------------------------------------------------
phpcs FileName.php

phpcs folder/

Описание стандартов:
-------------------------------------------------------------------------
PSR-0: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md

PSR-1: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md

PSR-2: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md

Отличия от PSR-2:
- вместо пробелов табы

Отличия от PSR-1:
- namespace можно не указывать
