FROM wordpress:latest

RUN rm -f /usr/src/wordpress/readme.html \
    && rm -f /usr/src/wordpress/license.txt \
    && rm -f /var/www/html/readme.html \
    && rm -f /var/www/html/license.txt

COPY secure-htaccess.txt /usr/src/wordpress/.htaccess
RUN chown www-data:www-data /usr/src/wordpress/.htaccess