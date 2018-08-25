FROM ubuntu
MAINTAINER Chenxing 
ENV REFRESHED_AT 2018-08-21

RUN apt-get update && apt-get -y -q install nginx

RUN mkdir -p /var/www/html
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/nginx.conf

EXPOSE 80