FROM node:10-alpine

RUN apk add --no-cache make gcc g++ python zeromq zeromq-dev

ENV APP_DIR=/app

# Create app directory
RUN mkdir -p $APP_DIR && chown node:node $APP_DIR
