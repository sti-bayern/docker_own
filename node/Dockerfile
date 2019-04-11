FROM adbv/base

LABEL maintainer="Günther Morhart"

#
# Setup
#

RUN echo "http://dl-cdn.alpinelinux.org/alpine/latest-stable/main" >> /etc/apk/repositories
RUN apk add --no-cache \
        git \
        nodejs \
        nodejs-npm
