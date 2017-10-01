FROM php:7.0-fpm
RUN docker-php-ext-install pdo_mysql

# RUN apt-get update && apt-get install -y \
#         libfreetype6-dev \
#         libjpeg62-turbo-dev \
#         libmcrypt-dev \
#         libpng12-dev \
#         libpq-dev \
#         apt-utils \
#     && docker-php-ext-install -j$(nproc) mcrypt \
#     && docker-php-ext-configure gd --with-freetype-dir=/usr/include/ --with-jpeg-dir=/usr/include/ \
#     && docker-php-ext-install -j$(nproc) gd

# RUN apt-get update && apt-get install -y \
#         libmemcached11 \
#         libmemcachedutil2 \
#         libmemcached-dev \
#         libz-dev \
#         git \
#     && cd /root \
#     && git clone -b php7 https://github.com/php-memcached-dev/php-memcached \
#     && cd php-memcached \
#     && phpize \
#     && ./configure \
#     && make \
#     && make install \
#     && cd .. \
#     && rm -rf  php-memcached \
#     && echo extension=memcached.so >> /usr/local/etc/php/conf.d/memcached.ini \
#     && apt-get remove -y build-essential libmemcached-dev libz-dev \
#     && apt-get remove -y \
#         libmemcached-dev \
#         libz-dev \
#     && apt-get autoremove -y \
#     && rm -rf /var/lib/apt/lists/* \
#     && apt-get clean

# RUN  docker-php-ext-install mysqli && \
#      docker-php-ext-install pdo_mysql pdo_pgsql \

# # Clean up
# RUN apt-get clean && \
#     rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

# RUN usermod -u 1000 www-data

# WORKDIR /var/www


# https://github.com/laradock/laradock