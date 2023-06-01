FROM node:7

WORKDIR /usr/src/app

COPY package.json package.json

RUN yarn install

COPY server.js server.js

EXPOSE 80

ENTRYPOINT ["yarn", "start"]