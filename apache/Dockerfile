FROM httpd:2.4

COPY httpd.conf /usr/local/apache2/conf/
COPY httpd-proxy.conf /usr/local/apache2/conf/extra/

EXPOSE 80

CMD ["httpd", "-D", "FOREGROUND"]