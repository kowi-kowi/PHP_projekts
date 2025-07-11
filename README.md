# PHP_projekts

## Install LAMP on Rasbery PI

1. Update system:
`sudo apt update && sudo apt upgrade -y`

2. Install Apache:
`sudo apt install apache2 -y`

3. Check in webbrowser if Ahache works
`http://localhost`

4. Install PHP
`sudo apt install php libapache2-mod-php -y`

5. Install MariaDB
`sudo apt install mariadb-server php-mysql -y`

6. Secure DB
`sudo mysql_secure_installation`

7. Restart ahache server
`sudo systemctl restart apache2`

8. First PHP file 
> sudo nano /var/www/html/index.php

`<?php
phpinfo();
?>`

check in browser 
`http://localhost/index.php`


