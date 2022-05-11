FROM ubuntu
RUN apt update -y
RUN apt install apache2 -y
COPY repo /var/www/html
EXPOSE 80
CMD /usr/sbin/apache2
