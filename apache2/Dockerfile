FROM ubuntu:22.04

ENV APACHE_CONFDIR=/etc/apache2
ENV APACHE_ENVVARS=$APACHE_CONFDIR/envvars

WORKDIR /var/www/html

RUN apt update
RUN apt install -y apache2

COPY index.html /var/www/html/

CMD ["apachectl", "-D", "FOREGROUND"]

# ENTRYPOINT ["echo", "default"]
# CMD ["addcmd"]
