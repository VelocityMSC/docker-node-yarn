FROM node:12.18.1-slim
MAINTAINER Steven Cook <scook@velocity.org>

RUN apt-get update && \
    apt-get install -y curl apt-transport-https gnupg2 && \
    curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | apt-key add - && \
    echo "deb https://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list && \
    apt-get update && apt-get install -y yarn perl libperl-dev

WORKDIR /workspace
