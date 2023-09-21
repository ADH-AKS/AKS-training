FROM ubuntu:latest

RUN apt-get update -y && apt-get install nginx systemctl curl -y

COPY ./index.html /var/www/html/

CMD ["systemctl", "start", "nginx"]
