FROM ubuntu
RUN apt update && apt install nginx -y
RUN rm -rf /var/www/html/*
COPY . /var/www/html/
