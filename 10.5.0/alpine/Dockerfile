FROM node:10.5.0-alpine

MAINTAINER Steven Cook <scook@velocity.org>

# Most dependencies are already installed from the base image

RUN apk update --no-cache --no-progress && \
    apk upgrade --no-cache --no-progress && \
    apk add --no-cache --no-progress alpine-sdk perl perl-dev

WORKDIR /workspace
