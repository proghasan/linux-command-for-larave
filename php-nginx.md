# How to install nginx
    1. sudo apt install nginx
# How to install php
    1. sudo apt install software-properties-common
    2. sudo add-apt-repository ppa:ondrej/php
    3. sudo apt update
    4. sudo apt install php8.0
    5. sudo apt search php8.0-* 
    6. sudo apt install php8.0-gd php8.0-xml php8.0-soap php8.0-mbstring php8.0-mysql 
    
# Switch Default PHP Version
    1. sudo update-alternatives --config php
    
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
