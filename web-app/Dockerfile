FROM node:19-alpine as node

WORKDIR /home/node/app

RUN apk add git

RUN git clone https://github.com/mat-twg/example-web-app.git .

RUN yarn
