FROM php:7.1-apache

RUN a2enmod rewrite
ADD php.ini /usr/local/etc/php/php.ini

RUN mkdir /app
WORKDIR /app

RUN usermod -u 1000 www-data
RUN chown www-data:www-data /app

