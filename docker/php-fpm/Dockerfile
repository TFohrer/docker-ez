FROM ezsystems/php:7.3-v1-node
#FROM php:fpm-alpine

#COPY wait-for-it.sh /usr/bin/wait-for-it

#RUN chmod +x /usr/bin/wait-for-it

#RUN apk --update --no-cache add git

#RUN docker-php-ext-install pdo_mysql

# install intl

COPY --from=composer /usr/bin/composer /usr/bin/composer

WORKDIR /var/www

#CMD composer install ;  php-fpm

EXPOSE 9000
