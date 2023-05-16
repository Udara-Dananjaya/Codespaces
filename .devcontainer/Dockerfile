FROM php:8.0-apache
RUN /usr/local/bin/docker-php-ext-install mysqli pdo pdo_mysql \
    && apt update \
    && apt install -y git curl \
    && curl -sL https://deb.nodesource.com/setup_14.x | bash \
    && apt update \
    && apt-get -y install nodejs \
    && npm i -g jshint;
    