# lamp-setup
This is a simple setup script using whiplash to display comands in a menu type seting to install a LAMP server on 
Debian based sytems.
# Screenshots
## Main Screen
![Main menu](/doc/images/main.png)
## Apache Setup
![Apache menu](/doc/images/apache.png)
## MySql
![Mysql Menu](/doc/images/mysql.png)
## Extras
![Extras menu](/doc/images/extra.png)
# Usage
To use this repository download the code from this repository and run lamp-setup by typing in 
`./lamp-setup`
from your terminal
you might have to type in
`chmod +X lamp-setup`
to make the file executable. Run the menu from the first option down so 
1. Update - This will update your repositorys as well as upgrade your programs.
 The next three menu Items will install a basic LAMP server onto your Debian OS
2. Apache2
3. MySql
4. PHP
5. Config Options - This will let you edit the config files for apache php and MariaDB - a mysql alternative as well
as making backups of your current config files and an option to restore from the backups
6. Extras - this installs aditional programs used in the creation of websites as well as an option to instal phphmyadmin
7. About - just a basic message about the tool
8. Tutorial - basic tutorial on how to add functions and menu items
# Installation
If you want to make this script advailable to all users type
`cp lamp-setup /bin`
If you want to make this advailable to the current logged in user type
`cp lamp-setup /usr/bin`
and run it in a terminal with
`lamp-setup`
