# README #

### Deploy NGINX and PHP-fpm on Debian (nice work with GET Simple CMS) ###

* Version 15.07.16

### How do I get set up? ###

* Install nginx: `apt-get install nginx`
* Install PHP: `apt-get install php5-cli php5-common php5-mysql php5-gd php5-fpm php5-cgi php5-fpm php-pear php5-mcrypt`
* Stop nginx service: `service nginx stop`
* Stop php-fpm service: `service php5-fpm stop`
* Copy config files
* Restart php-fpm service: `service php5-fpm restart`
* Copy site files to www directory
* Start nginx service: `service nginx start`

### Who do I talk to? ###

* Repo owner CyberManiac