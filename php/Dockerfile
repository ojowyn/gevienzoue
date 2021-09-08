FROM php:fpm-alpine

MAINTAINER Dominique DELEPINE <ddelepine@gmail.com>

VOLUME /var/www/html

RUN apk update; \
    apk upgrade;
RUN docker-php-ext-install mysqli