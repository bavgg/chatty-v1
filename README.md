# chatty-v1
Tuned version of chatty tutorial 


## Docker run command used for lamp:
docker run -it -p 8080:80 -p 3306:3306 -p 8001:8000 -v ~/htmls:/var/www/html --name chatty-container ubuntu_lamp:chatty /bin/bash -c "/etc/init.d/mysql start && /etc/init.d/apache2 start && /bin/bash"


## Git commands used:
 git clone https://github.com/bavgg/chatty-v1.git

## Packages needed to be installed:
 (but before that update apt) npm, composer, php
 
## Create laravel project:
composer create-project laravel/laravel chatty-v1

!!! Remove unnecessary files

!!! Database configuration env file

!!! Run "php arisan serve"

