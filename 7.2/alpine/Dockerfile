FROM php:7.2-fpm-alpine
RUN apk update && apk add ssmtp libpng-dev libfreetype-dev libjpeg-turbo-dev
RUN docker-php-ext-configure gd --with-freetype-dir=/usr/include/ --with-png-dir=/usr/include/ --with-jpeg-dir=/usr/include/
RUN docker-php-ext-install mysqli pdo_mysql gd
