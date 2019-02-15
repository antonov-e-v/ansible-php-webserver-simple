# ansible-php-webserver-simple
Install some services for php web applications

Installs:
- Fail2ban
- Ufw
- Php with some important extensions
- Nginx 
- MariaDB
- Git
- Composer
- python-mysqldb

Creates:
- user with name `webmaster` and password `password` (don't forget to change it)
- database with name `app_db`
- database user with name `app_user` and password `app_user_password` (don't forget to change it) and all priveleges to `app_db`

This environment was successfully tested with Laravel project.
