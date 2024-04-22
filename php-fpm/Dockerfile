FROM php:8.2-fpm

RUN apt update
RUN apt install -y curl git
RUN docker-php-ext-install mysqli pdo pdo_mysql

WORKDIR /var/www/html

ENTRYPOINT [ "php-fpm" ]