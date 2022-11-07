PHP 8.1

    Ubuntu 22

        sudo apt update
        sudo apt install --no-install-recommends php8.1
        php -v
    
    
    Ubuntu 20
    
        sudo add-apt-repository ppa:ondrej/php
        sudo apt install php8.0
        php -v

Composer

    sudo apt install composer
    composer -v

Laravel

    composer create-project laravel/laravel laravel-psicologia -v
    
    if needed

        sudo apt-get install php-curl
        sudo apt-get install php-xml
