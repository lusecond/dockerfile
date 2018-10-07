FROM php:7-fpm

RUN apt-get update \
	&& apt-get install -y libcurl3-dev \
	&& docker-php-ext-install mysqli pdo_mysql \
	&& yes | pecl install igbinary msgpack redis yaf yar \
	&& yes | pecl install "channel://pecl.php.net/yac-2.0.2" \
	&& docker-php-ext-enable igbinary msgpack redis yaf yar yac 
