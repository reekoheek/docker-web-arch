FROM debian:wheezy

MAINTAINER Ganesha <reekoheek@gmail.com>

COPY root/etc/apt /etc/apt

RUN apt-get update -y

RUN apt-get install -y nginx

COPY root/ /

EXPOSE 80

CMD ["nginx"]