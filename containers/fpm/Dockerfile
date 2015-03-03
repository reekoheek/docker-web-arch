FROM debian:wheezy

MAINTAINER Ganesha <reekoheek@gmail.com>

COPY root/etc/apt /etc/apt

RUN apt-get update -y

RUN apt-get install -y php5-fpm php5-mcrypt php5-xdebug

COPY root/ /

EXPOSE 9000

CMD ["php5-fpm", "-F"]