# Nginx
FROM nginx:1.17

RUN mkdir /logs
RUN mkdir -p /var/www/html-acme-challenge
RUN mkdir -p /var/www/html-staging
RUN mkdir -p /var/www/html-www

COPY nginx.conf   /etc/nginx/nginx.conf

VOLUME /logs
VOLUME /var/www/html-acme-challenge
VOLUME /var/www/html-staging
VOLUME /var/www/html-www
VOLUME /etc/nginx/conf.d
