# Dockerfile
FROM php:8.1-apache

COPY ./app/ /var/www/html/
COPY ./docker/php/conf.d/ /usr/local/etc/php/conf.d/
COPY ./docker/php/apm-agent-php_1.10.0_all.deb /var/www/apm-agent/apm-agent-php_1.10.0_all.deb

RUN dpkg -i /var/www/apm-agent/apm-agent-php_1.10.0_all.deb && apt-get install -f

