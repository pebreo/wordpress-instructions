http://codex.wordpress.org/Installing_WordPress_Locally_on_Your_Mac_With_MAMP

install MAMP
 - click on DMG file
 - click MAMP.app file
 - click preferences


Configure MAMP for Wordpress
 - click Preferences
 - click Apache 
 - change document root to: /Users/pebb/workspace/wordpress
 
Configure local servers
 - click Start Servers on the MAMP.app
 - when the webpage opens click phpMyAdmin
 - under Databases, "Create New Database" create a database called wordpress or something

Download Wordpress
 - goto wordpress.org and download the tar.gz
 - extract the wordpress file by: tar xfz wordpress..tar.gz
 - move that folder to /Users/pebb/workspace
 
Configure Wordpress:
 - goto: http://localhost:8888/
 - then follow the forms and enter the following:
 Database Name: wordpress
User Name (database): root
Password (database): root
Database Host/server: localhost
Table Prefix: wp_


Other resources:

https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-on-ubuntu-12-04

https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-nginx-on-ubuntu-12-04