# vagrant
The Big Hot Vagrant Machine

## Stack

* Apache2
* Apache2 Modules
    * headers
    * rewrite
    * ssl
* Composer
* Git
* MySQL
* PHP-7.2 in Development mode
    * php7.2-curl
    * php7.2-gd
    * php7.2-mbstring
    * php7.2-mysql
    * php7.2-xml
    * php7.2-zip
    * php7-dev
* PHPUnit-7.1



* phpMyAdmin
* PHPUnit

## Install

Make directory "~/.EvgenyMazanik-vagrant" .
Change directories for "/host" and "/config" directories for config.vm.synced_folder param.
Add all hosts to the host file:
    192.168.111.72 phpmyadmin
    192.168.111.72 test.dev
