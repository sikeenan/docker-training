# Simple Docker file
FROM ubuntu:18.04

USER  root

COPY ./docker-entrypoint.sh /docker-entrypoint.sh

RUN  chmod 755 /docker-entrypoint.sh

ENTRYPOINT /docker-entrypoint.sh
