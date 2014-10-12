## Environment
- PHP 5.5.9-1ubuntu4.4 (cli) (built: Sep  4 2014 06:56:34)
- Apache/2.4.7 (Ubuntu)
- [PHPExcel](https://phpexcel.codeplex.com/)

## Setup .htaccess
- add setting in /etc/apache2/sites-available/default
```
<Directory /var/www/>
    Options Indexes FollowSymLinks MultiViews
    AllowOverride All
    Order allow,deny
    allow from all
</Directory>
```
- a2enmod rewrite
- a2enmod headers
- service apache2 restart
