FROM php:7.4-fpm
WORKDIR "/"

RUN apt update

RUN apt-get update && \
    apt-get install -y \
        zlib1g-dev libpng-dev libicu-dev

RUN docker-php-ext-install gd intl mysqli