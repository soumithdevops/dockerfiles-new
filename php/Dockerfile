FROM php:7.0-apache
RUN apt-get update && \
apt-get install -y php-mysql && \
apt-get clean

#step to inject the latest code.

COPY myapp /var/www/html
