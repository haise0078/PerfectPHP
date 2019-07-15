FROM php:7.2-fpm
RUN apt-get update \
    && apt-get install -y mysql-client libpq-dev \
    && docker-php-ext-install pdo_mysql pdo_pgsql
COPY php.ini /usr/local/etc/php/

