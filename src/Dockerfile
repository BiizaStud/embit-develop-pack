FROM php:8.0-apache

WORKDIR /var/www/html

RUN docker-php-ext-install mysqli 
RUN docker-php-ext-enable mysqli

RUN apt-get update && apt-get upgrade -y