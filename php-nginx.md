# How to install nginx
    1. sudo apt install nginx
    2. sudo ufw app list
    3. sudo ufw enable
    4. sudo ufw allow 'Nginx HTTP'
    5. sudo ufw status
    6. sudo ufw allow 22
    7. sudo systemctl restart nginx
    
# How to install php
    1. sudo apt install software-properties-common
    2. sudo add-apt-repository ppa:ondrej/php
    3. sudo apt update
    4. sudo apt install php8.0
    5. sudo apt search php8.0-* 
    6. sudo apt install php8.0-gd php8.0-xml php8.0-soap php8.0-mbstring php8.0-mysql 
    
# Switch Default PHP Version
    1. sudo update-alternatives --config php
    
# Composer 2 install
    1. sudo apt update
    2. sudo apt install php-cli unzip
    3. sudo apt install curl
    https://www.digitalocean.com/community/tutorials/how-to-install-composer-on-ubuntu-20-04-quickstart
    
# How to install mysql
    1. sudo apt install mysql-server
    2. sudo mysql_secure_installation
    3. sudo mysql
    4. SELECT user,authentication_string,plugin,host FROM mysql.user;
    5. ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
    6. FLUSH PRIVILEGES;
    7. SELECT user,authentication_string,plugin,host FROM mysql.user;
    8. exit
    9. mysql -u root -p
