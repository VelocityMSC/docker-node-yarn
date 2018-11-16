FROM node:6.14.4-slim

MAINTAINER Steven Cook <scook@velocity.org>

RUN apt-get -y update && \
    apt-get -y install curl apt-transport-https perl libperl-dev && \
    mkdir -p /workspace

WORKDIR /workspace
