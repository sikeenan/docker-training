# Simple Docker file
FROM ubuntu:18.04

USER  root

RUN apt-get update -y && \
    apt-get install -y \
        curl \
        python3 \
        python3-pip

COPY ./docker-entrypoint.sh /docker-entrypoint.sh

RUN  chmod 755 /docker-entrypoint.sh

ENTRYPOINT /docker-entrypoint.sh
