FROM node:6

ENV DEBIAN_FRONTEND noninteractive
RUN apt-get -y update && \
    apt-get install -y --no-install-recommends apt-utils && \
    apt-get install -y graphicsmagick \