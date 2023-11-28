FROM phpdockerio/php:8.2-fpm
WORKDIR "/application"

RUN apt-get update \
    && apt-get -y --no-install-recommends install \
        php8.2-bz2 \ 
        php8.2-cgi \ 
        php8.2-dba \ 
        php8.2-decimal \ 
        php8.2-ds \ 
        php8.2-gmp \ 
        php8.2-gnupg \ 
        php8.2-grpc \ 
        php8.2-http \ 
        php8.2-imap \ 
        php8.2-mcrypt \ 
        php8.2-memcache \ 
        php8.2-memcached \ 
        php8.2-mysql \ 
        php8.2-odbc \ 
        php8.2-phpdbg \ 
        php8.2-psr \ 
        php8.2-yaml \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
