FROM php:fpm

# install mysqli extension
RUN docker-php-ext-install mysqli
# install pdo extension
RUN docker-php-ext-install pdo_mysql

CMD ["php-fpm"]
EXPOSE 9000