FROM phpdockerio/php:8.3-fpm
WORKDIR "/application"

RUN apt-get update \
    && apt-get -y --no-install-recommends install \
        php8.3-gd \
        php8.3-mcrypt \
        php8.3-pgsql \
        php8.3-soap \
        php8.3-sqlite3 \
    && apt-get clean \
    && chmod 777 /application -R \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
