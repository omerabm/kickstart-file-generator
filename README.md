# About
generate kickstart files for your linux installation

## Features
- upload csv file with you server details
- create kickstart files automatically
- works as well for ESX installations

## Screenshots
![webinterface](/doc/screenshots/webinterface.jpg?raw=true "Login")  
![boot](/doc/screenshots/boot.jpg?raw=true "Login")

## Installation
- upload file to your webserver
- edit centos-template.cfg and change the setting to match your needs
- edit upload/.htaccess to match the path
- upload users are stored in upload/.htpasswd (default user1/user1)
- add user or change password: htpasswd .htpasswd myusername

## Usage
- boot from the CentOS installation iso file (netinstall or full depending on the kickstart file  
- press tab during the installation selection menu
- add ks=http://webserver/path/centos.php?hostname=myservername
- wait until the installation finished

