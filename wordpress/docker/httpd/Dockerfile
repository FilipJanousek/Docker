FROM httpd:2.4.51

COPY extension.apache.conf /usr/local/apache2/conf/extension.apache.conf

RUN echo "Include /usr/local/apache2/conf/extension.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf
