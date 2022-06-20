FROM php:8.1-fpm
COPY upload.ini /usr/local/etc/php/conf.d
RUN docker-php-ext-install mysqli
RUN usermod -u 1000 www-data