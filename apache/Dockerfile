FROM httpd:latest

MAINTAINER Dominique DELEPINE <ddelepine@gmail.com>

VOLUME $HTTPD_PREFIX/conf/extra/virtualhost

VOLUME /var/www/html

RUN echo "Include conf/extra/virtualhost/*" | tee -a /usr/local/apache2/conf/httpd.conf

RUN chown www-data:www-data /var/www/html; \
    chmod 777 /var/www/html
