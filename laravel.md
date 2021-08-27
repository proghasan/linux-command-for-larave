# After install php
    1. sudo apt-get install php8.0-mbstring
    2. sudo apt-get install php-xml

# Image lib for image convert
    1. sudo apt-get install php8.0-gd


# Vue js cli install errors
    1. sudo chown -R $USER /usr/local/lib


# File public path problem fixed on linux
    1. sudo chmod o+x $HOME
    2. sudo systemctl restart apache2
    
    
 # Php curl enable
    1. sudo apt-get install php8.0-curl
    2. extension=curl.so
    3. sudo /etc/init.d/apache2 restart
