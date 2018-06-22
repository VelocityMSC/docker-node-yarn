FROM node:4.3.2-wheezy

MAINTAINER Steven Cook <scook@velocity.org>

# Global install yarn package manager
RUN npm set progress=false && \
    npm install -g --progress=false yarn

WORKDIR /workspace
