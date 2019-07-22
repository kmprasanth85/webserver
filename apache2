FROM ubuntu:16.04
MAINTAINER Prasanth
RUN apt-get update -y
RUN apt-get install -y apache2
COPY index.html /var/www/html/
EXPOSE 8082:80
CMD /usr/sbin/apache2ctl -D FOREGROUND

