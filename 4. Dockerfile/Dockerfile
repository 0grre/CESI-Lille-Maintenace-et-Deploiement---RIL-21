FROM debian:latest
RUN apt update -yqq && apt upgrade -yqq
RUN echo "coucou" > /tmp/coucou.txt
RUN echo "This is my own image based on Debian"

RUN apt install -yqq apache2 && apt clean
RUN service apache2 start
RUN echo "ServerName AirBnb" >> /etc/apache2/apache2.conf
RUN echo "AirBnb" > /var/www/html/index.html

EXPOSE 80
EXPOSE 433