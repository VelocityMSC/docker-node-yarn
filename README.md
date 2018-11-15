# NODEJS DOCKER IMAGE WITH YARN PACKAGE MANAGER AND PERL SUPPORT

Github Source: https://hub.docker.com/r/velocityorg/node-yarn-perl/
Docker Hub:

## Notes
- The `latest` tag currently points to `node:8.12.0-stretch` (Debian 9 stretch), as our Gitlab runner build jobs fail with NodeJS >= 9, due to unmet dependencies. This is deprecated and will be fixed in a future release.
- We do not support the NodeJS `onbuild` images, as these are deprecated.

## Supported tags and respective `Dockerfile` links

-   [`latest` (*8.12.0/stretch/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/8.12.0/stretch/Dockerfile)
-   [`6.14.4-alpine`, (*6.14.4/alpine/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/6.14.4/alpine/Dockerfile)
-   [`6.14.4-jessie`, (*6.14.4/jessie/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/6.14.4/jessie/Dockerfile)
-   [`6.14.4-slim`, (*6.14.4/slim/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/6.14.4/slim/Dockerfile)
-   [`6.14.4-stretch`, (*6.14.4/stretch/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/6.14.4/stretch/Dockerfile)
-   [`8.12.0-alpine`, (*8.12.0/alpine/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/8.11.3/alpine/Dockerfile)
-   [`8.12.0-jessie`, (*8.12.0/jessie/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/8.11.3/jessie/Dockerfile)
-   [`8.12.0-slim`, (*8.12.0/slim/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/8.11.3/slim/Dockerfile)
-   [`8.12.0-stretch`, (*8.12.0/stretch/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/8.11.3/stretch/Dockerfile)
-   [`10.13.0-alpine`, (*10.13.0/alpine/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/10.13.0/alpine/Dockerfile)
-   [`10.13.0-jessie`, (*10.13.0/jessie/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/10.13.0/jessie/Dockerfile)
-   [`10.13.0-slim`, (*10.13.0/slim/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/10.13.0/slim/Dockerfile)
-   [`10.13.0-stretch`, (*10.13.0/stretch/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/10.13.0/stretch/Dockerfile)
-   [`11.1.0-alpine`, (*11.1.0/alpine/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/11.1.0/alpine/Dockerfile)
-   [`11.1.0-jessie`, (*11.1.0/jessie/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/11.1.0/jessie/Dockerfile)
-   [`11.1.0-slim`, (*11.1.0/slim/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/11.1.0/slim/Dockerfile)
-   [`11.1.0-stretch`, (*11.1.0/stretch/Dockerfile*)](https://github.com/velocityorg/docker-node-yarn/blob/master/11.1.0/stretch/Dockerfile)

## Links

- DockerHub NodeJS images: https://hub.docker.com/_/node/
- Yarn package manager: https://yarnpkg.com/
