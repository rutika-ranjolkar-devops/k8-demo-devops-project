FROM node:16-alpine3.13

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

COPY package.json /usr/src/app/
RUN npm install

COPY . /usr/src/app

USER node
CMD [ "node", "index.js" ]
