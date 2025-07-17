FROM php:7.4-apache
RUN a2enmod rewrite
WORKDIR /var/www/html
COPY ./wordpress/ .
RUN chown -R www-data:www-data /var/www/html
RUN docker-php-ext-install mysqli
EXPOSE 80



