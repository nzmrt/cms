cms
===



Virtualhost ayarlar�
C:\xampp\apache\conf\extra\httpd-vhosts.conf
====================

NameVirtualHost *:80
<VirtualHost *:80>
        ServerAdmin webmaster@localhost
        SetEnv APPLICATION_ENV development
        DocumentRoot "C:/xampp/htdocs/cmspanel/modules/cms/public"
        ServerName cmspanel
        <Directory />
                Options FollowSymLinks
                AllowOverride All
        </Directory>        
</VirtualHost>
<VirtualHost *:80>
        ServerAdmin webmaster@localhost
        SetEnv APPLICATION_ENV development
        DocumentRoot "C:/xampp/htdocs/cmspanel/modules/site/public"
        ServerName hediyenikap
        <Directory />
                Options FollowSymLinks
                AllowOverride All
        </Directory>        
</VirtualHost>


host dosyas� ayarlar�
127.0.0.1       localhost cmspanel hediyenikap
