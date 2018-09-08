FROM node:alpine

LABEL maintainer="jason@ciandt.com"

RUN npm install -g webpack webpack-dev-server \
  && npm cache clean --force

VOLUME /app

WORKDIR /app