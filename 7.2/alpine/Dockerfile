FROM php:7.2-fpm-alpine
RUN apk update && apk add ssmtp
RUN docker-php-ext-install mysqli pdo_mysql
