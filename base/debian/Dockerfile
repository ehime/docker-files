FROM debian:latest

MAINTAINER Jd Daniel <dodomeki@gmail.com>

RUN apt-get update          \
  && apt-get -y upgrade     \
  && apt-get -y autoclean   \
  && apt-get -y autoremove  \
  && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

COPY ./bin/gosu /usr/local/bin/gosu
