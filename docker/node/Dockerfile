FROM node:14.21

WORKDIR /var/www/html

USER root:root

RUN apt-get update \
    && apt-get install \
    git vim \
    -y \
    && apt-get clean

USER www-data:www-data
