FROM node:8.12.0-alpine

MAINTAINER Steven Cook <scook@velocity.org>

RUN apk update --no-cache --no-progress && \
    apk upgrade --no-cache --no-progress && \
    apk add --no-cache --no-progress alpine-sdk bash perl perl-dev && \
    mkdir -p /workspace

WORKDIR /workspace
