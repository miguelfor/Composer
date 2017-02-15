# Composer

ingresa a la url y se descarga segun el sistema operativo

https://getcomposer.org/

si sale un error se abre el php.ini y se habilita el ssl paar que deje instalar

extension=php_openss.dll // toca descomentar
los archivos json se guardan con utf8(asegurar al guardar como utf8) no deves usar el BOMl


https://packagist.org/ en esta url podemos buscar todos los packages

creo una carpeta composer con un archivo json composer.json con los componentes que voy a instalar
despues voy por consola a la carpeta composer y le doy  composer install
me empieza a instalar todos los componentes

o si no por consola directamente
composer require phpmailer/phpmailer //directamente me los descarga
