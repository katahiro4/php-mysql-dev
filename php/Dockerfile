FROM php:8.1.9-fpm

RUN apt-get update \
    && docker-php-ext-install pdo_mysql

COPY php.ini /usr/local/etc/php/