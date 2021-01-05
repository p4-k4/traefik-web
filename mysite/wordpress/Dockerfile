FROM wordpress
RUN pecl install redis && docker-php-ext-enable redis
RUN /etc/init.d/apache2 restart