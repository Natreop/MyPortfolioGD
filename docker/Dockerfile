FROM php:8.0-apache

COPY . /var/www/html/

RUN echo "DirectoryIndex index.html" > /etc/apache2/conf-available/fallback-index.conf \
 && a2enconf fallback-index

EXPOSE 80
