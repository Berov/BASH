# Linux Installations Helper  


1. **Apache Installation:**  

  _sudo apt install apache2_  
  _sudo chown -R pi:www-data /var/www/html/_  
  _sudo chmod -R 770 /var/www/html/_  

  Apache's configuration files on Debian:
  /etc/apache2/  
    |-- apache2.conf  
    |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--  ports.conf  
    |-- mods-enabled  
    |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-- *.load  
    |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\`-- *.conf  
    |-- conf-enabled  
    |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\`-- *.conf  
    |-- sites-enabled  
    |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-- *.conf  

----------------------------------------   
2. **PHP Installation:**  
  _sudo apt-get install php php-mbstring_  
  __Ex. create page:__ _echo "\<?php phpinfo();?>" > /var/www/html/info.php_  
  **_php -v_** - показва версията  
 
 ----------------------------------------   
3. **MySQL Workbench Installation:**  
  _sudo apt-get install msql-workbench_
  
  ----------------------------------------   
4. **MS Fonts Installation:**  
  _sudo apt install ttf-mscorefonts-installer_  
  _sudo fc-cache -f -v_  
  
  ----------------------------------------  
5. **Flash Player Instalation**  
  sudo add-apt-repository "deb http://archive.canonical.com/ $(lsb_release -sc) partner"  
  sudo apt update  
  sudo apt install adobe-flashplugin browser-plugin-freshplayer-pepperflash  
  
  
