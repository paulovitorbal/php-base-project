FROM phpdockerio/php:8.1-fpm
WORKDIR "/application"

RUN apt-get update; \
    apt-get -y --no-install-recommends install \
        git \ 
        php8.1-amqp \ 
        php8.1-memcached \ 
        php8.1-mysql \ 
        php8.1-oauth \ 
        php8.1-pgsql \ 
        php8.1-protobuf \ 
        php8.1-psr \ 
        php8.1-redis \ 
        php8.1-sqlite3 \ 
        php8.1-ssh2 \ 
        php8.1-xdebug \ 
        php8.1-yaml; \
    apt-get clean; \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
