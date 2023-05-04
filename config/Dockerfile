FROM library/php:8.2.2-fpm

RUN docker-php-ext-install pdo pdo_mysql opcache

WORKDIR /var/www/app
COPY ./src ./

EXPOSE 9000
CMD /bin/bash -c "php-fpm"