FROM node:12-alpine

ENV HOME=/usr/src/app
RUN mkdir -p $HOME
WORKDIR $HOME

RUN yarn global add @angular/cli

EXPOSE 4200

USER 1000